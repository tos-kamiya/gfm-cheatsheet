<style>
* {
    font-family: 'PlemolJP', monospace;
}
span.mcode {
    background-color: #ddd;
    margin: 0.1em;
    padding: 0.2em;
}
</style>

## Markdown(GFM) チートシート

※ <span class="mcode">␣</span>は省略できないスペース

**見出し(H1〜H6)** 行頭で <span class="mcode">#␣見出し1</span> <span class="mcode">##␣見出し2</span> など

**連番** 行頭で <span class="mcode">1.␣文</span> <span class="mcode">2.␣文</span> など

**箇条書き** 行頭で <span class="mcode">&#42;␣文</span>または<span class="mcode">-␣文</span>または<span class="mcode">+␣文</span>
* 入れ子にするときは字下げする <span class="mcode">␣␣&#42;␣文</span>

**強調/打ち消し** <span class="mcode">&#42;&#42;強調したい文字列&#42;&#42;</span> <span class="mcode">&#126;&#126;打ち消したい文字列&#126;&#126;</span>

**水平線** 行頭で <span class="mcode">---</span>

**リンク** <span class="mcode">&#91;リンクの見出し&#93;(https://〜URL〜)</span>または<span class="mcode">&lt;https://〜URL〜&gt;</span>

**画像** <span class="mcode">!&#91;&#93;(URLまたはファイルのパス)</span>

**HTML埋め込み** HTMLのタグ<span class="mcode"><....></span>や特殊文字<span class="mcode">&....;</span>をそのまま書く

**改行** 行末にスペースを2つ（<span class="mcode">␣␣</span>）書くと行間の小さい改行。空白行を書くと通常の改行

**行内埋め込みコード** <span class="mcode">&#96;コード&#96;</span> (バッククオートで囲う）

**引用** 行頭で <span class="mcode">&gt; 文</span>

* 引用の行が続くと、まとめて1つの引用ブロックとしてレンダリングされる

**タスクリストアイテム** 行頭で <span class="mcode">*␣&#91;␣&#93;␣アイテム</span>または<span class="mcode">*␣&#91;x&#93;␣アイテム</span>

* &#91;x&#93;の方はチェックマークつき（完了したタスクの意味）

**コードブロック**  
<div style="background-color:#ddd">&#96;&#96;&#96;<br>
コード<br>
&#96;&#96;&#96;</div>

* 1行目の<span class="mcode">&#96;&#96;&#96;</span>の後ろに言語の名前を書くとシンタックスハイライトされる

**テーブル**
<div style="background-color:#ddd">| ヘッダ1 | ヘッダ2 | ヘッダ3 |<br>
| --- | --- | --- |<br>
| 項目11 | 項目12 | 項目13 |<br>
| 項目21 | 項目22 | 項目23 |
</div>

* ヘッダ行と<span class="mcode">|---|</span>の行は省略できない。<span class="mcode">---</span>は3文字以上であれば、何文字でもよい

**絵文字** <span style="background-color: #ddd;">:</span><span style="background-color: #ddd;">+1</span><span style="background-color: #ddd;">:</span> など。参照 <https://gist.github.com/rxaviers/7360908>
