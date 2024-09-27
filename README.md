# tmuxのカスタム設定

設定を反映させるには↓を実行

```
tmux source path-to-config/.tmux.conf
```

## コマンド一覧

prefix = \<C-j\>

| コマンド          | 役割                                   |
| ----------------- | -------------------------------------- |
| prefix + ?        | キーバインド一覧                       |
| prefix + s        | セッションの一覧表示                   |
| prefix + c        | 新規ウィンドウ作成・追加               |
| prefix + w        | ウィンドウの一覧                       |
| prefix + &        | ウインドウの破棄                       |
| prefix + n        | 次のウインドウへ移動                   |
| prefix + p        | 前のウインドウへ移動                   |
| prefix + \|       | 左右にペイン分割                       |
| prefix + -        | 上下にペイン分割                       |
| prefix + h        | 左のペインに移動                       |
| prefix + j        | 下のペインに移動                       |
| prefix + k        | 上のペインに移動                       |
| prefix + l        | 右のペインに移動                       |
| prefix + H        | ペインを左にリサイズ                   |
| prefix + J        | ペインを下にリサイズ                   |
| prefix + K        | ペインを上にリサイズ                   |
| prefix + L        | ペインを右にリサイズ                   |
| prefix + x        | ペインの破棄                           |
| prefix + スペース | ペインのレイアウト変更                 |
| prefix + Ctrl + o | ペインの入れ替え                       |
| prefix + {        | ペインの入れ替え(上方向)               |
| prefix + }        | ペインの入れ替え(下方向)               |
| prefix + [        | コピーモードの開始(カーソルキーで移動) |
| prefix + v        | コピー開始位置決定(viモード)           |
| prefix + y        | コピー終了位置決定(viモード)           |
| prefix + Ctrl + p | コピー内容の貼り付け                   |
