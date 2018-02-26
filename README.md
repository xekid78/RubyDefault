# RubyDefault
引数のデフォルト値

## 処理
メソッドで引数を省略した場合に利用できるデフォルト値を設定する。

## コード
```
def introduce(name = "ほにゃらら")
    puts "私は#{name}です。"
end

introduce("私")
introduce()
```

## 出力結果  
```
私は私です。
私はほにゃららです。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
