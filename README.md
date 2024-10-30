<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="8086117" _msthash="364">Kipoi 模型</h2><a id="user-content-kipoi-models" class="anchor" aria-label="永久链接：Kipoi 模型" href="#kipoi-models" _mstaria-label="478296" _msthash="365"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://circleci.com/gh/kipoi/models" rel="nofollow"><img src="https://camo.githubusercontent.com/9e0c824fa1227874a76273b3b8980d6798f4baa681748756eaf6f8be97aaaedc/68747470733a2f2f636972636c6563692e636f6d2f67682f6b69706f692f6d6f64656c732e7376673f7374796c653d73766726636972636c652d746f6b656e3d65653932613932616362323838653137333939363630653636363033663730303733376537333832" alt="圆CI" data-canonical-src="https://circleci.com/gh/kipoi/models.svg?style=svg&amp;circle-token=ee92a92acb288e17399660e66603f700737e7382" style="max-width: 100%;" _mstalt="99034" _msthash="366"></a> <a href="https://zenodo.org/badge/latestdoi/103403966" rel="nofollow"><img src="https://camo.githubusercontent.com/e46177af959d16cebfac8bce1727f19acc372ebb3e3e1641af83e933fba027b7/68747470733a2f2f7a656e6f646f2e6f72672f62616467652f3130333430333936362e737667" alt="数字对象标识符" data-canonical-src="https://zenodo.org/badge/103403966.svg" style="max-width: 100%;" _mstalt="22945" _msthash="367"></a></p>
<p dir="auto"><font _mstmutation="1" _msttexthash="406578185" _msthash="368">此存储库托管基因组学的预测模型，并用作 <a href="https://github.com/kipoi/kipoi" _mstmutation="1" _istranslated="1">Kipoi</a> 的模型源。包含的每个文件夹都被视为单个模型。</font><code>model.yaml</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="12446486" _msthash="369">贡献模型</h3><a id="user-content-contributing-models" class="anchor" aria-label="永久链接：贡献模型" href="#contributing-models" _mstaria-label="784927" _msthash="370"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li _msttexthash="17736693" _msthash="371">安装 kipoi：</li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install kipoi</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install kipoi" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="2" dir="auto">
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="41615210" _msthash="372">跑。这会将存储库签出到</font><code>kipoi ls</code><code>kipoi/models</code><code>~/.kipoi/models</code>)</p>
</li>
<li>
<p dir="auto" _msttexthash="131264068" _msthash="373">按照 <a href="https://kipoi.org/docs/contributing/01_Getting_started/" rel="nofollow" _istranslated="1">contributing/Getting started</a> 中的说明进行操作。</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="114638420" _msthash="374">使用模型（预测、评分变体、构建新模型）</h3><a id="user-content-using-models-to-predict-score-variants-build-new-models" class="anchor" aria-label="永久链接：使用模型（预测、评分变体、构建新模型）" href="#using-models-to-predict-score-variants-build-new-models" _mstaria-label="2987985" _msthash="375"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="955149286" _msthash="376">要了解可用模型，请访问 <a href="http://kipoi.org/groups/" rel="nofollow" _istranslated="1">http://kipoi.org/models</a>。有关如何使用 CLI、python 或 R 以编程方式访问此存储库中的模型的更多信息，请参阅 <a href="https://github.com/kipoi/kipoi" _istranslated="1">kipoi/README.md</a> 和 <a href="http://kipoi.org/docs/using/01_Getting_started/" rel="nofollow" _istranslated="1">docs/using 入门</a>。</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="28702492" _msthash="377">配置本地存储位置</h4><a id="user-content-configuring-local-storage-location" class="anchor" aria-label="永久链接：配置本地存储位置" href="#configuring-local-storage-location" _mstaria-label="1519271" _msthash="378"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="414084957" _msthash="379">默认情况下，此模型源 （<a href="https://github.com/kipoi/models" _mstmutation="1" _istranslated="1">https://github.com/kipoi/models</a>） 包含在 Kipoi 配置文件 （） 中：</font><code>~/.kipoi/config.yaml</code></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> ~/.kipoi/config.yaml</span>
<span class="pl-ent">model_sources</span>:
    <span class="pl-ent">kipoi</span>:
        <span class="pl-ent">type</span>: <span class="pl-s">git-lfs</span>
        <span class="pl-ent">remote_url</span>: <span class="pl-s">git@github.com:kipoi/models.git</span>
        <span class="pl-ent">local_path</span>: <span class="pl-s">~/.kipoi/models/</span>
        <span class="pl-ent">auto_update</span>: <span class="pl-c1">True</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# ~/.kipoi/config.yaml
model_sources:
    kipoi:
        type: git-lfs
        remote_url: git@github.com:kipoi/models.git
        local_path: ~/.kipoi/models/
        auto_update: True" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="148556135" _msthash="380">如果您希望将模型存储在其他位置，请相应地编辑 。</font><code>local_path</code></p>
</article></div>
