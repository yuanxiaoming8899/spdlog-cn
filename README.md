<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志记录</font></font></h1><a id="user-content-spdlog" class="anchor" aria-label="永久链接：spdlog" href="#spdlog"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常快、仅标头/已编译的 C++ 日志库。</font></font><a href="https://github.com/gabime/spdlog/actions/workflows/ci.yml"><img src="https://github.com/gabime/spdlog/actions/workflows/ci.yml/badge.svg" alt="词" style="max-width: 100%;"></a>&nbsp; <a href="https://ci.appveyor.com/project/gabime/spdlog" rel="nofollow"><img src="https://camo.githubusercontent.com/423449d754237746747637aee42fa93e6c9d9dc4d22ce326b595771dc3e1c82e/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f64326a6e78636c6732307664306f35303f7376673d74727565266272616e63683d76312e78" alt="构建状态" data-canonical-src="https://ci.appveyor.com/api/projects/status/d2jnxclg20vd0o50?svg=true&amp;branch=v1.x" style="max-width: 100%;"></a> <a href="https://github.com/gabime/spdlog/releases/latest"><img src="https://camo.githubusercontent.com/42552d0e168353f52db0d98e48ab042127d85f45c539ad15b861bb17659d3324/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f676162696d652f7370646c6f672e737667" alt="发布" data-canonical-src="https://img.shields.io/github/release/gabime/spdlog.svg" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-install" class="anchor" aria-label="永久链接：安装" href="#install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅标头版本</font></font></h4><a id="user-content-header-only-version" class="anchor" aria-label="永久链接：仅标题版本" href="#header-only-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 include</font></font><a href="https://github.com/gabime/spdlog/tree/v1.x/include/spdlog"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复制到构建树并使用 C++11 编译器。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译版本（推荐 - 编译时间更快）</font></font></h4><a id="user-content-compiled-version-recommended---much-faster-compile-times" class="anchor" aria-label="永久链接：编译版本（推荐 - 编译时间更快）" href="#compiled-version-recommended---much-faster-compile-times"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-s1">git clone https://github.com/gabime/spdlog.git</span>
$ <span class="pl-s1"><span class="pl-c1">cd</span> spdlog <span class="pl-k">&amp;&amp;</span> mkdir build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build</span>
$ <span class="pl-s1">cmake .. <span class="pl-k">&amp;&amp;</span> make -j</span></pre><div class="zeroclipboard-container">
   
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux、FreeBSD、OpenBSD、Solaris、AIX</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows（msvc 2013+、cygwin）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS（clang 3.5+）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安卓</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包管理器：</font></font></h2><a id="user-content-package-managers" class="anchor" aria-label="永久链接：包管理器：" href="#package-managers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">德班：</font></font><code>sudo apt install libspdlog-dev</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自制：</font></font><code>brew install spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mac 端口：</font></font><code>sudo port install spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自由BSD：  </font></font><code>pkg install spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽：</font></font><code>dnf install spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根图：</font></font><code>emerge dev-libs/spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拱门Linux：</font></font><code>pacman -S spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放SUSE：</font></font><code>sudo zypper in spdlog-devel</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vcpkg：</font></font><code>vcpkg install spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">柯南：</font></font><code>spdlog/[&gt;=1.4.1]</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">康达：</font></font><code>conda install -c conda-forge spdlog</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建2：</font></font><code>depends: spdlog ^1.8.2</code></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h2><a id="user-content-features" class="anchor" aria-label="永久链接：特点" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常快（参见下面的</font></font><a href="#benchmarks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅标头或已编译</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能丰富的格式化，使用优秀的</font></font><a href="https://github.com/fmtlib/fmt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">fmt</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步模式（可选）</font></font></li>
<li><a href="https://github.com/gabime/spdlog/wiki/3.-Custom-formatting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格式。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多/单线程记录器。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">各种日志目标：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轮换日志文件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每日日志文件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">控制台日志记录（支持颜色）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统日志。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 事件日志。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 调试器 ( </font></font><code>OutputDebugString(..)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">登录到 Qt 小部件（</font></font><a href="#log-to-qt-with-nice-colors"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过自定义日志目标轻松</font></font><a href="https://github.com/gabime/spdlog/wiki/4.-Sinks#implementing-your-own-sink"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩展</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志过滤 - 日志级别可以在运行时和编译时修改。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持从 argv 或环境变量加载日志级别。</font></font></li>
<li><a href="#backtrace-support"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回溯</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 - 将调试消息存储在环形缓冲区中并稍后根据需要显示它们。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用示例</font></font></h2><a id="user-content-usage-samples" class="anchor" aria-label="永久链接：使用示例" href="#usage-samples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本用法</font></font></h4><a id="user-content-basic-usage" class="anchor" aria-label="永久链接：基本用法" href="#basic-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/spdlog.h<span class="pl-pds">"</span></span>

<span class="pl-k">int</span> <span class="pl-en">main</span>() 
{
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>Welcome to spdlog!<span class="pl-pds">"</span></span>);
    <span class="pl-c1">spdlog::error</span>(<span class="pl-s"><span class="pl-pds">"</span>Some error message with arg: {}<span class="pl-pds">"</span></span>, <span class="pl-c1">1</span>);
    
    <span class="pl-c1">spdlog::warn</span>(<span class="pl-s"><span class="pl-pds">"</span>Easy padding in numbers like {:08d}<span class="pl-pds">"</span></span>, <span class="pl-c1">12</span>);
    <span class="pl-c1">spdlog::critical</span>(<span class="pl-s"><span class="pl-pds">"</span>Support for int: {0:d};  hex: {0:x};  oct: {0:o}; bin: {0:b}<span class="pl-pds">"</span></span>, <span class="pl-c1">42</span>);
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>Support for floats {:03.2f}<span class="pl-pds">"</span></span>, <span class="pl-c1">1.23456</span>);
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>Positional args are {1} {0}..<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>too<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>supported<span class="pl-pds">"</span></span>);
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>{:&lt;30}<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>left aligned<span class="pl-pds">"</span></span>);
    
    <span class="pl-c1">spdlog::set_level</span>(spdlog::level::debug); <span class="pl-c"><span class="pl-c">//</span> Set global log level to debug</span>
    <span class="pl-c1">spdlog::debug</span>(<span class="pl-s"><span class="pl-pds">"</span>This message should be displayed..<span class="pl-pds">"</span></span>);    
    
    <span class="pl-c"><span class="pl-c">//</span> change log pattern</span>
    <span class="pl-c1">spdlog::set_pattern</span>(<span class="pl-s"><span class="pl-pds">"</span>[%H:%M:%S %z] [%n] [%^---%L---%$] [thread %t] %v<span class="pl-pds">"</span></span>);
    
    <span class="pl-c"><span class="pl-c">//</span> Compile time log levels</span>
    <span class="pl-c"><span class="pl-c">//</span> Note that this does not change the current log level, it will only</span>
    <span class="pl-c"><span class="pl-c">//</span> remove (depending on SPDLOG_ACTIVE_LEVEL) the call on the release code.</span>
    <span class="pl-c1">SPDLOG_TRACE</span>(<span class="pl-s"><span class="pl-pds">"</span>Some trace message with param {}<span class="pl-pds">"</span></span>, <span class="pl-c1">42</span>);
    <span class="pl-c1">SPDLOG_DEBUG</span>(<span class="pl-s"><span class="pl-pds">"</span>Some debug message<span class="pl-pds">"</span></span>);
}
</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建 stdout/stderr 记录器对象</font></font></h4><a id="user-content-create-stdoutstderr-logger-object" class="anchor" aria-label="永久链接：创建 stdout/stderr 记录器对象" href="#create-stdoutstderr-logger-object"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/spdlog.h<span class="pl-pds">"</span></span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/stdout_color_sinks.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">stdout_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> create a color multi-threaded logger</span>
    <span class="pl-k">auto</span> console = <span class="pl-c1">spdlog::stdout_color_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>console<span class="pl-pds">"</span></span>);    
    <span class="pl-k">auto</span> err_logger = <span class="pl-c1">spdlog::stderr_color_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>stderr<span class="pl-pds">"</span></span>);    
    <span class="pl-c1">spdlog::get</span>(<span class="pl-s"><span class="pl-pds">"</span>console<span class="pl-pds">"</span></span>)-&gt;<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>loggers can be retrieved from a global registry using the spdlog::get(logger_name)<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/spdlog.h&quot;
#include &quot;spdlog/sinks/stdout_color_sinks.h&quot;
void stdout_example()
{
    // create a color multi-threaded logger
    auto console = spdlog::stdout_color_mt(&quot;console&quot;);    
    auto err_logger = spdlog::stderr_color_mt(&quot;stderr&quot;);    
    spdlog::get(&quot;console&quot;)->info(&quot;loggers can be retrieved from a global registry using the spdlog::get(logger_name)&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本文件记录器</font></font></h4><a id="user-content-basic-file-logger" class="anchor" aria-label="永久链接：基本文件记录器" href="#basic-file-logger"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/basic_file_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">basic_logfile_example</span>()
{
    <span class="pl-k">try</span> 
    {
        <span class="pl-k">auto</span> logger = <span class="pl-c1">spdlog::basic_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>basic_logger<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/basic-log.txt<span class="pl-pds">"</span></span>);
    }
    <span class="pl-k">catch</span> (<span class="pl-k">const</span> spdlog::spdlog_ex &amp;ex)
    {
        std::cout &lt;&lt; <span class="pl-s"><span class="pl-pds">"</span>Log init failed: <span class="pl-pds">"</span></span> &lt;&lt; ex.<span class="pl-c1">what</span>() &lt;&lt; std::endl;
    }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/sinks/basic_file_sink.h&quot;
void basic_logfile_example()
{
    try 
    {
        auto logger = spdlog::basic_logger_mt(&quot;basic_logger&quot;, &quot;logs/basic-log.txt&quot;);
    }
    catch (const spdlog::spdlog_ex &amp;ex)
    {
        std::cout << &quot;Log init failed: &quot; << ex.what() << std::endl;
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">旋转文件</font></font></h4><a id="user-content-rotating-files" class="anchor" aria-label="永久链接：旋转文件" href="#rotating-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/rotating_file_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">rotating_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> Create a file rotating logger with 5 MB size max and 3 rotated files</span>
    <span class="pl-k">auto</span> max_size = <span class="pl-c1">1048576</span> * <span class="pl-c1">5</span>;
    <span class="pl-k">auto</span> max_files = <span class="pl-c1">3</span>;
    <span class="pl-k">auto</span> logger = <span class="pl-c1">spdlog::rotating_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>some_logger_name<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/rotating.txt<span class="pl-pds">"</span></span>, max_size, max_files);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/sinks/rotating_file_sink.h&quot;
void rotating_example()
{
    // Create a file rotating logger with 5 MB size max and 3 rotated files
    auto max_size = 1048576 * 5;
    auto max_files = 3;
    auto logger = spdlog::rotating_logger_mt(&quot;some_logger_name&quot;, &quot;logs/rotating.txt&quot;, max_size, max_files);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每日档案</font></font></h4><a id="user-content-daily-files" class="anchor" aria-label="固定链接：每日档案" href="#daily-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/daily_file_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">daily_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> Create a daily logger - a new file is created every day at 2:30 am</span>
    <span class="pl-k">auto</span> logger = <span class="pl-c1">spdlog::daily_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>daily_logger<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/daily.txt<span class="pl-pds">"</span></span>, <span class="pl-c1">2</span>, <span class="pl-c1">30</span>);
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="
#include &quot;spdlog/sinks/daily_file_sink.h&quot;
void daily_example()
{
    // Create a daily logger - a new file is created every day at 2:30 am
    auto logger = spdlog::daily_logger_mt(&quot;daily_logger&quot;, &quot;logs/daily.txt&quot;, 2, 30);
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回溯支持</font></font></h4><a id="user-content-backtrace-support" class="anchor" aria-label="永久链接：回溯支持" href="#backtrace-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> Debug messages can be stored in a ring buffer instead of being logged immediately.</span>
<span class="pl-c"><span class="pl-c">//</span> This is useful to display debug logs only when needed (e.g. when an error happens).</span>
<span class="pl-c"><span class="pl-c">//</span> When needed, call dump_backtrace() to dump them to your log.</span>

<span class="pl-en">spdlog::enable_backtrace</span>(<span class="pl-c1">32</span>); <span class="pl-c"><span class="pl-c">//</span> Store the latest 32 messages in a buffer. </span>
<span class="pl-c"><span class="pl-c">//</span> or my_logger-&gt;enable_backtrace(32)..</span>
<span class="pl-k">for</span>(<span class="pl-k">int</span> i = <span class="pl-c1">0</span>; i &lt; <span class="pl-c1">100</span>; i++)
{
  <span class="pl-c1">spdlog::debug</span>(<span class="pl-s"><span class="pl-pds">"</span>Backtrace message {}<span class="pl-pds">"</span></span>, i); <span class="pl-c"><span class="pl-c">//</span> not logged yet..</span>
}
<span class="pl-c"><span class="pl-c">//</span> e.g. if some error happened:</span>
<span class="pl-en">spdlog::dump_backtrace</span>(); <span class="pl-c"><span class="pl-c">//</span> log them now! show the last 32 messages</span>
<span class="pl-c"><span class="pl-c">//</span> or my_logger-&gt;dump_backtrace(32)..</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Debug messages can be stored in a ring buffer instead of being logged immediately.
// This is useful to display debug logs only when needed (e.g. when an error happens).
// When needed, call dump_backtrace() to dump them to your log.

spdlog::enable_backtrace(32); // Store the latest 32 messages in a buffer. 
// or my_logger->enable_backtrace(32)..
for(int i = 0; i < 100; i++)
{
  spdlog::debug(&quot;Backtrace message {}&quot;, i); // not logged yet..
}
// e.g. if some error happened:
spdlog::dump_backtrace(); // log them now! show the last 32 messages
// or my_logger->dump_backtrace(32).." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定期冲洗</font></font></h4><a id="user-content-periodic-flush" class="anchor" aria-label="永久链接：定期冲洗" href="#periodic-flush"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> periodically flush all *registered* loggers every 3 seconds:</span>
<span class="pl-c"><span class="pl-c">//</span> warning: only use if all your loggers are thread-safe ("_mt" loggers)</span>
<span class="pl-en">spdlog::flush_every</span>(std::chrono::seconds(<span class="pl-c1">3</span>));
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// periodically flush all *registered* loggers every 3 seconds:
// warning: only use if all your loggers are thread-safe (&quot;_mt&quot; loggers)
spdlog::flush_every(std::chrono::seconds(3));
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑表</font></font></h4><a id="user-content-stopwatch" class="anchor" aria-label="永久链接：秒表" href="#stopwatch"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> Stopwatch support for spdlog</span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/stopwatch.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">stopwatch_example</span>()
{
    spdlog::stopwatch sw;    
    <span class="pl-c1">spdlog::debug</span>(<span class="pl-s"><span class="pl-pds">"</span>Elapsed {}<span class="pl-pds">"</span></span>, sw);
    <span class="pl-c1">spdlog::debug</span>(<span class="pl-s"><span class="pl-pds">"</span>Elapsed {:.3}<span class="pl-pds">"</span></span>, sw);       
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Stopwatch support for spdlog
#include &quot;spdlog/stopwatch.h&quot;
void stopwatch_example()
{
    spdlog::stopwatch sw;    
    spdlog::debug(&quot;Elapsed {}&quot;, sw);
    spdlog::debug(&quot;Elapsed {:.3}&quot;, sw);       
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以十六进制记录二进制数据</font></font></h4><a id="user-content-log-binary-data-in-hex" class="anchor" aria-label="永久链接：以十六进制记录二进制数据" href="#log-binary-data-in-hex"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> many types of std::container&lt;char&gt; types can be used.</span>
<span class="pl-c"><span class="pl-c">//</span> ranges are supported too.</span>
<span class="pl-c"><span class="pl-c">//</span> format flags:</span>
<span class="pl-c"><span class="pl-c">//</span> {:X} - print in uppercase.</span>
<span class="pl-c"><span class="pl-c">//</span> {:s} - don't separate each byte with space.</span>
<span class="pl-c"><span class="pl-c">//</span> {:p} - don't print the position on each line start.</span>
<span class="pl-c"><span class="pl-c">//</span> {:n} - don't split the output into lines.</span>
<span class="pl-c"><span class="pl-c">//</span> {:a} - show ASCII if :n is not set.</span>

#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/fmt/bin_to_hex.h<span class="pl-pds">"</span></span>

<span class="pl-k">void</span> <span class="pl-en">binary_example</span>()
{
    <span class="pl-k">auto</span> console = <span class="pl-c1">spdlog::get</span>(<span class="pl-s"><span class="pl-pds">"</span>console<span class="pl-pds">"</span></span>);
    std::array&lt;<span class="pl-k">char</span>, <span class="pl-c1">80</span>&gt; buf;
    console-&gt;<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>Binary example: {}<span class="pl-pds">"</span></span>, <span class="pl-c1">spdlog::to_hex</span>(buf));
    console-&gt;<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>Another binary example:{:n}<span class="pl-pds">"</span></span>, <span class="pl-c1">spdlog::to_hex</span>(<span class="pl-c1">std::begin</span>(buf), <span class="pl-c1">std::begin</span>(buf) + <span class="pl-c1">10</span>));
    <span class="pl-c"><span class="pl-c">//</span> more examples:</span>
    <span class="pl-c"><span class="pl-c">//</span> logger-&gt;info("uppercase: {:X}", spdlog::to_hex(buf));</span>
    <span class="pl-c"><span class="pl-c">//</span> logger-&gt;info("uppercase, no delimiters: {:Xs}", spdlog::to_hex(buf));</span>
    <span class="pl-c"><span class="pl-c">//</span> logger-&gt;info("uppercase, no delimiters, no position info: {:Xsp}", spdlog::to_hex(buf));</span>
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// many types of std::container<char> types can be used.
// ranges are supported too.
// format flags:
// {:X} - print in uppercase.
// {:s} - don't separate each byte with space.
// {:p} - don't print the position on each line start.
// {:n} - don't split the output into lines.
// {:a} - show ASCII if :n is not set.

#include &quot;spdlog/fmt/bin_to_hex.h&quot;

void binary_example()
{
    auto console = spdlog::get(&quot;console&quot;);
    std::array<char, 80> buf;
    console->info(&quot;Binary example: {}&quot;, spdlog::to_hex(buf));
    console->info(&quot;Another binary example:{:n}&quot;, spdlog::to_hex(std::begin(buf), std::begin(buf) + 10));
    // more examples:
    // logger->info(&quot;uppercase: {:X}&quot;, spdlog::to_hex(buf));
    // logger->info(&quot;uppercase, no delimiters: {:Xs}&quot;, spdlog::to_hex(buf));
    // logger->info(&quot;uppercase, no delimiters, no position info: {:Xsp}&quot;, spdlog::to_hex(buf));
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有多个接收器的记录器 - 每个接收器都有不同的格式和日志级别</font></font></h4><a id="user-content-logger-with-multi-sinks---each-with-a-different-format-and-log-level" class="anchor" aria-label="永久链接：具有多个接收器的记录器 - 每个接收器都有不同的格式和日志级别" href="#logger-with-multi-sinks---each-with-a-different-format-and-log-level"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> create a logger with 2 targets, with different log levels and formats.</span>
<span class="pl-c"><span class="pl-c">//</span> The console will show only warnings or errors, while the file will log all.</span>
<span class="pl-k">void</span> <span class="pl-en">multi_sink_example</span>()
{
    <span class="pl-k">auto</span> console_sink = std::make_shared&lt;spdlog::sinks::stdout_color_sink_mt&gt;();
    console_sink-&gt;<span class="pl-c1">set_level</span>(spdlog::level::warn);
    console_sink-&gt;<span class="pl-c1">set_pattern</span>(<span class="pl-s"><span class="pl-pds">"</span>[multi_sink_example] [%^%l%$] %v<span class="pl-pds">"</span></span>);

    <span class="pl-k">auto</span> file_sink = std::make_shared&lt;spdlog::sinks::basic_file_sink_mt&gt;(<span class="pl-s"><span class="pl-pds">"</span>logs/multisink.txt<span class="pl-pds">"</span></span>, <span class="pl-c1">true</span>);
    file_sink-&gt;<span class="pl-c1">set_level</span>(spdlog::level::trace);

    spdlog::logger <span class="pl-smi">logger</span>(<span class="pl-s"><span class="pl-pds">"</span>multi_sink<span class="pl-pds">"</span></span>, {console_sink, file_sink});
    logger.<span class="pl-c1">set_level</span>(spdlog::level::debug);
    logger.<span class="pl-c1">warn</span>(<span class="pl-s"><span class="pl-pds">"</span>this should appear in both console and file<span class="pl-pds">"</span></span>);
    logger.<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>this message should not appear in the console, only in the file<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="
// create a logger with 2 targets, with different log levels and formats.
// The console will show only warnings or errors, while the file will log all.
void multi_sink_example()
{
    auto console_sink = std::make_shared<spdlog::sinks::stdout_color_sink_mt>();
    console_sink->set_level(spdlog::level::warn);
    console_sink->set_pattern(&quot;[multi_sink_example] [%^%l%$] %v&quot;);

    auto file_sink = std::make_shared<spdlog::sinks::basic_file_sink_mt>(&quot;logs/multisink.txt&quot;, true);
    file_sink->set_level(spdlog::level::trace);

    spdlog::logger logger(&quot;multi_sink&quot;, {console_sink, file_sink});
    logger.set_level(spdlog::level::debug);
    logger.warn(&quot;this should appear in both console and file&quot;);
    logger.info(&quot;this message should not appear in the console, only in the file&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户定义的有关日志事件的回调</font></font></h4><a id="user-content-user-defined-callbacks-about-log-events" class="anchor" aria-label="永久链接：用户定义的有关日志事件的回调" href="#user-defined-callbacks-about-log-events"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> create a logger with a lambda function callback, the callback will be called</span>
<span class="pl-c"><span class="pl-c">//</span> each time something is logged to the logger</span>
<span class="pl-k">void</span> <span class="pl-en">callback_example</span>()
{
    <span class="pl-k">auto</span> callback_sink = std::make_shared&lt;spdlog::sinks::callback_sink_mt&gt;([](<span class="pl-k">const</span> spdlog::details::log_msg &amp;msg) {
         <span class="pl-c"><span class="pl-c">//</span> for example you can be notified by sending an email to yourself</span>
    });
    callback_sink-&gt;<span class="pl-c1">set_level</span>(spdlog::level::err);

    <span class="pl-k">auto</span> console_sink = std::make_shared&lt;spdlog::sinks::stdout_color_sink_mt&gt;();
    spdlog::logger <span class="pl-smi">logger</span>(<span class="pl-s"><span class="pl-pds">"</span>custom_callback_logger<span class="pl-pds">"</span></span>, {console_sink, callback_sink});

    logger.<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>some info log<span class="pl-pds">"</span></span>);
    logger.<span class="pl-c1">error</span>(<span class="pl-s"><span class="pl-pds">"</span>critical issue<span class="pl-pds">"</span></span>); <span class="pl-c"><span class="pl-c">//</span> will notify you</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="
// create a logger with a lambda function callback, the callback will be called
// each time something is logged to the logger
void callback_example()
{
    auto callback_sink = std::make_shared<spdlog::sinks::callback_sink_mt>([](const spdlog::details::log_msg &amp;msg) {
         // for example you can be notified by sending an email to yourself
    });
    callback_sink->set_level(spdlog::level::err);

    auto console_sink = std::make_shared<spdlog::sinks::stdout_color_sink_mt>();
    spdlog::logger logger(&quot;custom_callback_logger&quot;, {console_sink, callback_sink});

    logger.info(&quot;some info log&quot;);
    logger.error(&quot;critical issue&quot;); // will notify you
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步日志记录</font></font></h4><a id="user-content-asynchronous-logging" class="anchor" aria-label="永久链接：异步日志记录" href="#asynchronous-logging"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/async.h<span class="pl-pds">"</span></span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/basic_file_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">async_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> default thread pool settings can be modified *before* creating the async logger:</span>
    <span class="pl-c"><span class="pl-c">//</span> spdlog::init_thread_pool(8192, 1); // queue with 8k items and 1 backing thread.</span>
    <span class="pl-k">auto</span> async_file = spdlog::basic_logger_mt&lt;spdlog::async_factory&gt;(<span class="pl-s"><span class="pl-pds">"</span>async_file_logger<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/async_log.txt<span class="pl-pds">"</span></span>);
    <span class="pl-c"><span class="pl-c">//</span> alternatively:</span>
    <span class="pl-c"><span class="pl-c">//</span> auto async_file = spdlog::create_async&lt;spdlog::sinks::basic_file_sink_mt&gt;("async_file_logger", "logs/async_log.txt");   </span>
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/async.h&quot;
#include &quot;spdlog/sinks/basic_file_sink.h&quot;
void async_example()
{
    // default thread pool settings can be modified *before* creating the async logger:
    // spdlog::init_thread_pool(8192, 1); // queue with 8k items and 1 backing thread.
    auto async_file = spdlog::basic_logger_mt<spdlog::async_factory>(&quot;async_file_logger&quot;, &quot;logs/async_log.txt&quot;);
    // alternatively:
    // auto async_file = spdlog::create_async<spdlog::sinks::basic_file_sink_mt>(&quot;async_file_logger&quot;, &quot;logs/async_log.txt&quot;);   
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有多个接收器的异步记录器</font></font></h4><a id="user-content-asynchronous-logger-with-multi-sinks" class="anchor" aria-label="永久链接：具有多个接收器的异步记录器" href="#asynchronous-logger-with-multi-sinks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/stdout_color_sinks.h<span class="pl-pds">"</span></span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/rotating_file_sink.h<span class="pl-pds">"</span></span>

<span class="pl-k">void</span> <span class="pl-en">multi_sink_example2</span>()
{
    <span class="pl-c1">spdlog::init_thread_pool</span>(<span class="pl-c1">8192</span>, <span class="pl-c1">1</span>);
    <span class="pl-k">auto</span> stdout_sink = std::make_shared&lt;spdlog::sinks::stdout_color_sink_mt &gt;();
    <span class="pl-k">auto</span> rotating_sink = std::make_shared&lt;spdlog::sinks::rotating_file_sink_mt&gt;(<span class="pl-s"><span class="pl-pds">"</span>mylog.txt<span class="pl-pds">"</span></span>, <span class="pl-c1">1024</span>*<span class="pl-c1">1024</span>*<span class="pl-c1">10</span>, <span class="pl-c1">3</span>);
    std::vector&lt;spdlog::sink_ptr&gt; sinks {stdout_sink, rotating_sink};
    <span class="pl-k">auto</span> logger = std::make_shared&lt;spdlog::async_logger&gt;(<span class="pl-s"><span class="pl-pds">"</span>loggername<span class="pl-pds">"</span></span>, sinks.<span class="pl-c1">begin</span>(), sinks.<span class="pl-c1">end</span>(), <span class="pl-c1">spdlog::thread_pool</span>(), spdlog::async_overflow_policy::block);
    <span class="pl-c1">spdlog::register_logger</span>(logger);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/sinks/stdout_color_sinks.h&quot;
#include &quot;spdlog/sinks/rotating_file_sink.h&quot;

void multi_sink_example2()
{
    spdlog::init_thread_pool(8192, 1);
    auto stdout_sink = std::make_shared<spdlog::sinks::stdout_color_sink_mt >();
    auto rotating_sink = std::make_shared<spdlog::sinks::rotating_file_sink_mt>(&quot;mylog.txt&quot;, 1024*1024*10, 3);
    std::vector<spdlog::sink_ptr> sinks {stdout_sink, rotating_sink};
    auto logger = std::make_shared<spdlog::async_logger>(&quot;loggername&quot;, sinks.begin(), sinks.end(), spdlog::thread_pool(), spdlog::async_overflow_policy::block);
    spdlog::register_logger(logger);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户定义类型</font></font></h4><a id="user-content-user-defined-types" class="anchor" aria-label="永久链接：用户定义的类型" href="#user-defined-types"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">template</span>&lt;&gt;
<span class="pl-k">struct</span> <span class="pl-en">fmt</span>::formatter&lt;my_type&gt; : fmt::formatter&lt;std::string&gt;
{
    <span class="pl-k">auto</span> <span class="pl-en">format</span>(my_type my, format_context &amp;ctx) <span class="pl-k">const</span> -&gt; decltype(ctx.out())
    {
        <span class="pl-k">return</span> <span class="pl-c1">format_to</span>(ctx.<span class="pl-c1">out</span>(), <span class="pl-s"><span class="pl-pds">"</span>[my_type i={}]<span class="pl-pds">"</span></span>, my.<span class="pl-smi">i</span>);
    }
};

<span class="pl-k">void</span> <span class="pl-en">user_defined_example</span>()
{
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>user defined type: {}<span class="pl-pds">"</span></span>, <span class="pl-c1">my_type</span>(<span class="pl-c1">14</span>));
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="template<>
struct fmt::formatter<my_type> : fmt::formatter<std::string>
{
    auto format(my_type my, format_context &amp;ctx) const -> decltype(ctx.out())
    {
        return format_to(ctx.out(), &quot;[my_type i={}]&quot;, my.i);
    }
};

void user_defined_example()
{
    spdlog::info(&quot;user defined type: {}&quot;, my_type(14));
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志模式中的用户定义标志</font></font></h4><a id="user-content-user-defined-flags-in-the-log-pattern" class="anchor" aria-label="永久链接：日志模式中用户定义的标志" href="#user-defined-flags-in-the-log-pattern"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> Log patterns can contain custom flags.</span>
<span class="pl-c"><span class="pl-c">//</span> the following example will add new flag '%*' - which will be bound to a &lt;my_formatter_flag&gt; instance.</span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/pattern_formatter.h<span class="pl-pds">"</span></span>
<span class="pl-k">class</span> <span class="pl-en">my_formatter_flag</span> : <span class="pl-k">public</span> <span class="pl-en">spdlog</span>::custom_flag_formatter
{
<span class="pl-k">public:</span>
    <span class="pl-k">void</span> <span class="pl-en">format</span>(<span class="pl-k">const</span> spdlog::details::log_msg &amp;, <span class="pl-k">const</span> std::<span class="pl-c1">tm</span> &amp;, spdlog::<span class="pl-c1">memory_buf_t</span> &amp;dest) <span class="pl-k">override</span>
    {
        std::string some_txt = <span class="pl-s"><span class="pl-pds">"</span>custom-flag<span class="pl-pds">"</span></span>;
        dest.<span class="pl-c1">append</span>(some_txt.<span class="pl-c1">data</span>(), some_txt.<span class="pl-c1">data</span>() + some_txt.<span class="pl-c1">size</span>());
    }

    std::unique_ptr&lt;custom_flag_formatter&gt; <span class="pl-en">clone</span>() <span class="pl-k">const</span> <span class="pl-k">override</span>
    {
        <span class="pl-k">return</span> spdlog::details::make_unique&lt;my_formatter_flag&gt;();
    }
};

<span class="pl-k">void</span> <span class="pl-en">custom_flags_example</span>()
{    
    <span class="pl-k">auto</span> formatter = std::make_unique&lt;spdlog::pattern_formatter&gt;();
    formatter-&gt;<span class="pl-smi">add_flag</span>&lt;my_formatter_flag&gt;(<span class="pl-s"><span class="pl-pds">'</span>*<span class="pl-pds">'</span></span>).<span class="pl-c1">set_pattern</span>(<span class="pl-s"><span class="pl-pds">"</span>[%n] [%*] [%^%l%$] %v<span class="pl-pds">"</span></span>);
    <span class="pl-c1">spdlog::set_formatter</span>(<span class="pl-c1">std::move</span>(formatter));
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Log patterns can contain custom flags.
// the following example will add new flag '%*' - which will be bound to a <my_formatter_flag> instance.
#include &quot;spdlog/pattern_formatter.h&quot;
class my_formatter_flag : public spdlog::custom_flag_formatter
{
public:
    void format(const spdlog::details::log_msg &amp;, const std::tm &amp;, spdlog::memory_buf_t &amp;dest) override
    {
        std::string some_txt = &quot;custom-flag&quot;;
        dest.append(some_txt.data(), some_txt.data() + some_txt.size());
    }

    std::unique_ptr<custom_flag_formatter> clone() const override
    {
        return spdlog::details::make_unique<my_formatter_flag>();
    }
};

void custom_flags_example()
{    
    auto formatter = std::make_unique<spdlog::pattern_formatter>();
    formatter->add_flag<my_formatter_flag>('*').set_pattern(&quot;[%n] [%*] [%^%l%$] %v&quot;);
    spdlog::set_formatter(std::move(formatter));
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义错误处理程序</font></font></h4><a id="user-content-custom-error-handler" class="anchor" aria-label="永久链接：自定义错误处理程序" href="#custom-error-handler"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">void</span> <span class="pl-en">err_handler_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> can be set globally or per logger(logger-&gt;set_error_handler(..))</span>
    <span class="pl-c1">spdlog::set_error_handler</span>([](<span class="pl-k">const</span> std::string &amp;msg) { <span class="pl-c1">spdlog::get</span>(<span class="pl-s"><span class="pl-pds">"</span>console<span class="pl-pds">"</span></span>)-&gt;<span class="pl-c1">error</span>(<span class="pl-s"><span class="pl-pds">"</span>*** LOGGER ERROR ***: {}<span class="pl-pds">"</span></span>, msg); });
    <span class="pl-c1">spdlog::get</span>(<span class="pl-s"><span class="pl-pds">"</span>console<span class="pl-pds">"</span></span>)-&gt;<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>some invalid message to trigger an error {}{}{}{}<span class="pl-pds">"</span></span>, <span class="pl-c1">3</span>);
}
</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="void err_handler_example()
{
    // can be set globally or per logger(logger->set_error_handler(..))
    spdlog::set_error_handler([](const std::string &amp;msg) { spdlog::get(&quot;console&quot;)->error(&quot;*** LOGGER ERROR ***: {}&quot;, msg); });
    spdlog::get(&quot;console&quot;)->info(&quot;some invalid message to trigger an error {}{}{}{}&quot;, 3);
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统日志</font></font></h4><a id="user-content-syslog" class="anchor" aria-label="永久链接：系统日志" href="#syslog"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/syslog_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">syslog_example</span>()
{
    std::string ident = <span class="pl-s"><span class="pl-pds">"</span>spdlog-example<span class="pl-pds">"</span></span>;
    <span class="pl-k">auto</span> syslog_logger = <span class="pl-c1">spdlog::syslog_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>syslog<span class="pl-pds">"</span></span>, ident, LOG_PID);
    syslog_logger-&gt;<span class="pl-c1">warn</span>(<span class="pl-s"><span class="pl-pds">"</span>This is warning that will end up in syslog.<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/sinks/syslog_sink.h&quot;
void syslog_example()
{
    std::string ident = &quot;spdlog-example&quot;;
    auto syslog_logger = spdlog::syslog_logger_mt(&quot;syslog&quot;, ident, LOG_PID);
    syslog_logger->warn(&quot;This is warning that will end up in syslog.&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安卓示例</font></font></h4><a id="user-content-android-example" class="anchor" aria-label="永久链接：Android 示例" href="#android-example"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/android_sink.h<span class="pl-pds">"</span></span>
<span class="pl-k">void</span> <span class="pl-en">android_example</span>()
{
    std::string tag = <span class="pl-s"><span class="pl-pds">"</span>spdlog-android<span class="pl-pds">"</span></span>;
    <span class="pl-k">auto</span> android_logger = <span class="pl-c1">spdlog::android_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>android<span class="pl-pds">"</span></span>, tag);
    android_logger-&gt;<span class="pl-c1">critical</span>(<span class="pl-s"><span class="pl-pds">"</span>Use <span class="pl-cce">\"</span>adb shell logcat<span class="pl-cce">\"</span> to view this message.<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/sinks/android_sink.h&quot;
void android_example()
{
    std::string tag = &quot;spdlog-android&quot;;
    auto android_logger = spdlog::android_logger_mt(&quot;android&quot;, tag);
    android_logger->critical(&quot;Use \&quot;adb shell logcat\&quot; to view this message.&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 env 变量或 argv 加载日志级别</font></font></h4><a id="user-content-load-log-levels-from-the-env-variable-or-argv" class="anchor" aria-label="永久链接：从 env 变量或 argv 加载日志级别" href="#load-log-levels-from-the-env-variable-or-argv"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/cfg/env.h<span class="pl-pds">"</span></span>
<span class="pl-k">int</span> <span class="pl-en">main</span> (<span class="pl-k">int</span> argc, <span class="pl-k">char</span> *argv[])
{
    <span class="pl-c1">spdlog::cfg::load_env_levels</span>();
    <span class="pl-c"><span class="pl-c">//</span> or from the command line:</span>
    <span class="pl-c"><span class="pl-c">//</span> ./example SPDLOG_LEVEL=info,mylogger=trace</span>
    <span class="pl-c"><span class="pl-c">//</span> #include "spdlog/cfg/argv.h" // for loading levels from argv</span>
    <span class="pl-c"><span class="pl-c">//</span> spdlog::cfg::load_argv_levels(argc, argv);</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/cfg/env.h&quot;
int main (int argc, char *argv[])
{
    spdlog::cfg::load_env_levels();
    // or from the command line:
    // ./example SPDLOG_LEVEL=info,mylogger=trace
    // #include &quot;spdlog/cfg/argv.h&quot; // for loading levels from argv
    // spdlog::cfg::load_argv_levels(argc, argv);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">那么你可以：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-s1"><span class="pl-k">export</span> SPDLOG_LEVEL=info,mylogger=trace</span>
$ <span class="pl-s1">./example</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export SPDLOG_LEVEL=info,mylogger=trace
$ ./example" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志文件打开/关闭事件处理程序</font></font></h4><a id="user-content-log-file-openclose-event-handlers" class="anchor" aria-label="永久链接：日志文件打开/关闭事件处理程序" href="#log-file-openclose-event-handlers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">//</span> You can get callbacks from spdlog before/after a log file has been opened or closed. </span>
<span class="pl-c"><span class="pl-c">//</span> This is useful for cleanup procedures or for adding something to the start/end of the log file.</span>
<span class="pl-k">void</span> <span class="pl-en">file_events_example</span>()
{
    <span class="pl-c"><span class="pl-c">//</span> pass the spdlog::file_event_handlers to file sinks for open/close log file notifications</span>
    spdlog::file_event_handlers handlers;
    handlers.<span class="pl-smi">before_open</span> = [](spdlog::<span class="pl-c1">filename_t</span> filename) { <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>Before opening {}<span class="pl-pds">"</span></span>, filename); };
    handlers.<span class="pl-smi">after_open</span> = [](spdlog::<span class="pl-c1">filename_t</span> filename, std::FILE *fstream) { <span class="pl-c1">fputs</span>(<span class="pl-s"><span class="pl-pds">"</span>After opening<span class="pl-cce">\n</span><span class="pl-pds">"</span></span>, fstream); };
    handlers.<span class="pl-smi">before_close</span> = [](spdlog::<span class="pl-c1">filename_t</span> filename, std::FILE *fstream) { <span class="pl-c1">fputs</span>(<span class="pl-s"><span class="pl-pds">"</span>Before closing<span class="pl-cce">\n</span><span class="pl-pds">"</span></span>, fstream); };
    handlers.<span class="pl-smi">after_close</span> = [](spdlog::<span class="pl-c1">filename_t</span> filename) { <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>After closing {}<span class="pl-pds">"</span></span>, filename); };
    <span class="pl-k">auto</span> my_logger = <span class="pl-c1">spdlog::basic_logger_st</span>(<span class="pl-s"><span class="pl-pds">"</span>some_logger<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/events-sample.txt<span class="pl-pds">"</span></span>, <span class="pl-c1">true</span>, handlers);        
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// You can get callbacks from spdlog before/after a log file has been opened or closed. 
// This is useful for cleanup procedures or for adding something to the start/end of the log file.
void file_events_example()
{
    // pass the spdlog::file_event_handlers to file sinks for open/close log file notifications
    spdlog::file_event_handlers handlers;
    handlers.before_open = [](spdlog::filename_t filename) { spdlog::info(&quot;Before opening {}&quot;, filename); };
    handlers.after_open = [](spdlog::filename_t filename, std::FILE *fstream) { fputs(&quot;After opening\n&quot;, fstream); };
    handlers.before_close = [](spdlog::filename_t filename, std::FILE *fstream) { fputs(&quot;Before closing\n&quot;, fstream); };
    handlers.after_close = [](spdlog::filename_t filename) { spdlog::info(&quot;After closing {}&quot;, filename); };
    auto my_logger = spdlog::basic_logger_st(&quot;some_logger&quot;, &quot;logs/events-sample.txt&quot;, true, handlers);        
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换默认记录器</font></font></h4><a id="user-content-replace-the-default-logger" class="anchor" aria-label="永久链接：替换默认记录器" href="#replace-the-default-logger"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">void</span> <span class="pl-en">replace_default_logger_example</span>()
{
    <span class="pl-k">auto</span> new_logger = <span class="pl-c1">spdlog::basic_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>new_default_logger<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>logs/new-default-log.txt<span class="pl-pds">"</span></span>, <span class="pl-c1">true</span>);
    <span class="pl-c1">spdlog::set_default_logger</span>(new_logger);
    <span class="pl-c1">spdlog::info</span>(<span class="pl-s"><span class="pl-pds">"</span>new logger log message<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="void replace_default_logger_example()
{
    auto new_logger = spdlog::basic_logger_mt(&quot;new_default_logger&quot;, &quot;logs/new-default-log.txt&quot;, true);
    spdlog::set_default_logger(new_logger);
    spdlog::info(&quot;new logger log message&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用漂亮的颜色登录到 Qt</font></font></h4><a id="user-content-log-to-qt-with-nice-colors" class="anchor" aria-label="永久链接：用漂亮的颜色登录到 Qt" href="#log-to-qt-with-nice-colors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/spdlog.h<span class="pl-pds">"</span></span>
#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">"</span>spdlog/sinks/qt_sinks.h<span class="pl-pds">"</span></span>
<span class="pl-en">MainWindow::MainWindow</span>(QWidget *parent) : QMainWindow(parent)
{
    <span class="pl-c1">setMinimumSize</span>(<span class="pl-c1">640</span>, <span class="pl-c1">480</span>);
    <span class="pl-k">auto</span> log_widget = <span class="pl-k">new</span> <span class="pl-c1">QTextEdit</span>(<span class="pl-c1">this</span>);
    <span class="pl-c1">setCentralWidget</span>(log_widget);
    <span class="pl-k">int</span> max_lines = <span class="pl-c1">500</span>; <span class="pl-c"><span class="pl-c">//</span> keep the text widget to max 500 lines. remove old lines if needed.</span>
    <span class="pl-k">auto</span> logger = <span class="pl-c1">spdlog::qt_color_logger_mt</span>(<span class="pl-s"><span class="pl-pds">"</span>qt_logger<span class="pl-pds">"</span></span>, log_widget, max_lines);
    logger-&gt;<span class="pl-c1">info</span>(<span class="pl-s"><span class="pl-pds">"</span>Some info message<span class="pl-pds">"</span></span>);
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;spdlog/spdlog.h&quot;
#include &quot;spdlog/sinks/qt_sinks.h&quot;
MainWindow::MainWindow(QWidget *parent) : QMainWindow(parent)
{
    setMinimumSize(640, 480);
    auto log_widget = new QTextEdit(this);
    setCentralWidget(log_widget);
    int max_lines = 500; // keep the text widget to max 500 lines. remove old lines if needed.
    auto logger = spdlog::qt_color_logger_mt(&quot;qt_logger&quot;, log_widget, max_lines);
    logger->info(&quot;Some info message&quot;);
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试</font></font></h2><a id="user-content-benchmarks" class="anchor" aria-label="永久链接：基准" href="#benchmarks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是在 Ubuntu 64 位、Intel i7-4770 CPU @ 3.40GHz 中完成的</font><font style="vertical-align: inherit;">一些</font></font><a href="https://github.com/gabime/spdlog/blob/v1.x/bench/bench.cpp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同步模式</font></font></h4><a id="user-content-synchronous-mode" class="anchor" aria-label="永久链接：同步模式" href="#synchronous-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>[info] **************************************************************
[info] Single thread, 1,000,000 iterations
[info] **************************************************************
[info] basic_st         Elapsed: 0.17 secs        5,777,626/sec
[info] rotating_st      Elapsed: 0.18 secs        5,475,894/sec
[info] daily_st         Elapsed: 0.20 secs        5,062,659/sec
[info] empty_logger     Elapsed: 0.07 secs       14,127,300/sec
[info] **************************************************************
[info] C-string (400 bytes). Single thread, 1,000,000 iterations
[info] **************************************************************
[info] basic_st         Elapsed: 0.41 secs        2,412,483/sec
[info] rotating_st      Elapsed: 0.72 secs        1,389,196/sec
[info] daily_st         Elapsed: 0.42 secs        2,393,298/sec
[info] null_st          Elapsed: 0.04 secs       27,446,957/sec
[info] **************************************************************
[info] 10 threads, competing over the same logger object, 1,000,000 iterations
[info] **************************************************************
[info] basic_mt         Elapsed: 0.60 secs        1,659,613/sec
[info] rotating_mt      Elapsed: 0.62 secs        1,612,493/sec
[info] daily_mt         Elapsed: 0.61 secs        1,638,305/sec
[info] null_mt          Elapsed: 0.16 secs        6,272,758/sec
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[info] **************************************************************
[info] Single thread, 1,000,000 iterations
[info] **************************************************************
[info] basic_st         Elapsed: 0.17 secs        5,777,626/sec
[info] rotating_st      Elapsed: 0.18 secs        5,475,894/sec
[info] daily_st         Elapsed: 0.20 secs        5,062,659/sec
[info] empty_logger     Elapsed: 0.07 secs       14,127,300/sec
[info] **************************************************************
[info] C-string (400 bytes). Single thread, 1,000,000 iterations
[info] **************************************************************
[info] basic_st         Elapsed: 0.41 secs        2,412,483/sec
[info] rotating_st      Elapsed: 0.72 secs        1,389,196/sec
[info] daily_st         Elapsed: 0.42 secs        2,393,298/sec
[info] null_st          Elapsed: 0.04 secs       27,446,957/sec
[info] **************************************************************
[info] 10 threads, competing over the same logger object, 1,000,000 iterations
[info] **************************************************************
[info] basic_mt         Elapsed: 0.60 secs        1,659,613/sec
[info] rotating_mt      Elapsed: 0.62 secs        1,612,493/sec
[info] daily_mt         Elapsed: 0.61 secs        1,638,305/sec
[info] null_mt          Elapsed: 0.16 secs        6,272,758/sec" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步模式</font></font></h4><a id="user-content-asynchronous-mode" class="anchor" aria-label="永久链接：异步模式" href="#asynchronous-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>[info] -------------------------------------------------
[info] Messages     : 1,000,000
[info] Threads      : 10
[info] Queue        : 8,192 slots
[info] Queue memory : 8,192 x 272 = 2,176 KB 
[info] -------------------------------------------------
[info] 
[info] *********************************
[info] Queue Overflow Policy: block
[info] *********************************
[info] Elapsed: 1.70784 secs     585,535/sec
[info] Elapsed: 1.69805 secs     588,910/sec
[info] Elapsed: 1.7026 secs      587,337/sec
[info] 
[info] *********************************
[info] Queue Overflow Policy: overrun
[info] *********************************
[info] Elapsed: 0.372816 secs    2,682,285/sec
[info] Elapsed: 0.379758 secs    2,633,255/sec
[info] Elapsed: 0.373532 secs    2,677,147/sec

</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[info] -------------------------------------------------
[info] Messages     : 1,000,000
[info] Threads      : 10
[info] Queue        : 8,192 slots
[info] Queue memory : 8,192 x 272 = 2,176 KB 
[info] -------------------------------------------------
[info] 
[info] *********************************
[info] Queue Overflow Policy: block
[info] *********************************
[info] Elapsed: 1.70784 secs     585,535/sec
[info] Elapsed: 1.69805 secs     588,910/sec
[info] Elapsed: 1.7026 secs      587,337/sec
[info] 
[info] *********************************
[info] Queue Overflow Policy: overrun
[info] *********************************
[info] Elapsed: 0.372816 secs    2,682,285/sec
[info] Elapsed: 0.379758 secs    2,633,255/sec
[info] Elapsed: 0.373532 secs    2,677,147/sec
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/gabime/spdlog/wiki/1.-QuickStart"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档可以在wiki</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">页面中找到</font><font style="vertical-align: inherit;">。</font></font></p>
<hr>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://www.jetbrains.com/?from=spdlog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JetBrains</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捐赠产品许可证来帮助开发</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">spdlog</font></font></strong> <a href="https://www.jetbrains.com/?from=spdlog" rel="nofollow"><img src="/gabime/spdlog/raw/v1.x/logos/jetbrains-variant-4.svg" width="94" align="center" style="max-width: 100%;"></a></p>
</article></div>
