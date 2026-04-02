---
layout: ../../layouts/Layout.astro
title: NEWS
---

<div class="markdown-content">

# NEWS
## お知らせ・最新情報

* **2026-04-02** - [第6回 日本蛋白質科学会 若手の会 交流会のお知らせ](/news/2026-04-02)
* **2026-04-02** - 若手の会HPをオープンしました！

[トップページに戻る](/)

</div>

<style>
    /* Markdownのテキストを装飾するCSS*/
    .markdown-content {
        position: relative;
        z-index: 10; /* 光の帯（z-index:1）やオーバーレイより手前に */
        padding: 5vw 10vw;
        color: #001533; /* フォントカラー */
        font-family: 'sans-if'; /* フォントタイプ */
        font-size: 1.2rem; /* フォントサイズ */
        letter-spacing: 0.05rem; /* 文字間隔 */
        line-height: 1.8;
    }

    /* # MEMORY に関する設定 */
    .markdown-content h1 {
        font-size: 5rem;
        font-style: italic;
        color: #003399;
        border-bottom: 5px solid #0055ff;
        display: inline-block;
        margin-bottom: 1rem;
        font-family:"Barlow Condensed";
    }

    /* ## 研究交流会について に関する設定 */
    .markdown-content h2 {
        color: #002266; /* フォントカラー */
        margin-bottom: 2rem;
        font-size: 2rem; /* フォントサイズ */
    }

    .markdown-content ul {
        list-style-type: none; /* デフォルトの黒丸（・）を消す */
        padding-left: 0;
        margin-bottom: 3rem;
    }

    /* --- NEWSページ特有のリスト装飾 --- */    
    .markdown-content li {
        margin-bottom: 1rem;
        padding-bottom: 0.5rem;
        border-bottom: 1px dashed #88bbff; /* 項目と項目の間に薄い青の破線を引く */
    }

    .markdown-content a {
        color: #0055ff;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s;
    }

    .markdown-content a:hover {
        color: #003399; /* マウスを乗せたら少し濃い青にする */
        text-decoration: underline;
    }
</style>