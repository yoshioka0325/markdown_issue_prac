# VSCodeでmermaidを利用する方法や便利な拡張機能
### 使用方法
1. Visual Studio Code で Markdown Preview Mermaid Support をインストールします。
2. Visual Studio Code で .md ファイルを作成します。
3. 以下のように記述します。

```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
上記の上の部分の```の横にmermaidと記述し、拡張機能でプレビューすると以下のようになります。
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
### 便利な拡張機能の例
- Mermaid記法をプレビューに表示する
>https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid
- Mermaid記法をハイライト表示
>https://marketplace.visualstudio.com/items?itemName=bpruitt-goddard.mermaid-markdown-syntax-highlighting
- Mermaid記法で表示される図を画像やPDFに出力
>https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf
- Mermaid記法で表示される図をスライドに出力
>https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

***
引用元　https://qiita.com/sato_kana/items/2a13f19017576488f017