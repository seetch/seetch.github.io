<!DOCTYPE html>
<html lang="ru">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>seetch</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&family=DM+Mono:wght@300;400&display=swap"
    rel="stylesheet">
  <style>
    *,
    *::before,
    *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    :root {
      --bg: #0a0a0b;
      --surface: #111113;
      --surface2: #17171a;
      --line: rgba(255, 255, 255, 0.07);
      --line2: rgba(255, 255, 255, 0.12);
      --muted: rgba(255, 255, 255, 0.3);
      --text: rgba(255, 255, 255, 0.88);
      --accent: #4af0c8;
      --accent-dim: rgba(74, 240, 200, 0.10);
      --accent-glow: rgba(74, 240, 200, 0.22);
    }

    html,
    body {
      width: 100%;
      height: 100%;
      overflow: hidden;
    }

    body {
      background: var(--bg);
      font-family: 'DM Mono', monospace;
      color: var(--text);
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      position: relative;
    }

    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 0;
      opacity: 0.4;
    }

    body::after {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(var(--line) 1px, transparent 1px),
        linear-gradient(90deg, var(--line) 1px, transparent 1px);
      background-size: 48px 48px;
      pointer-events: none;
      z-index: 0;
      animation: gridFade 1.2s ease forwards;
      opacity: 0;
    }

    @keyframes gridFade {
      to {
        opacity: 1;
      }
    }

    .corner {
      position: fixed;
      width: 40px;
      height: 40px;
      pointer-events: none;
      z-index: 1;
      opacity: 0;
      animation: cornerIn 0.8s 0.4s ease forwards;
    }

    .corner::before,
    .corner::after {
      content: '';
      position: absolute;
      background: var(--accent);
    }

    .corner::before {
      width: 100%;
      height: 1px;
      top: 0;
      left: 0;
    }

    .corner::after {
      width: 1px;
      height: 100%;
      top: 0;
      left: 0;
    }

    .corner.tl {
      top: 24px;
      left: 24px;
    }

    .corner.tr {
      top: 24px;
      right: 24px;
      transform: scaleX(-1);
    }

    .corner.bl {
      bottom: 24px;
      left: 24px;
      transform: scaleY(-1);
    }

    .corner.br {
      bottom: 24px;
      right: 24px;
      transform: scale(-1, -1);
    }

    @keyframes cornerIn {
      to {
        opacity: 1;
      }
    }

    .card {
      position: relative;
      z-index: 2;
      width: min(520px, calc(100vw - 48px));
      padding: 56px 52px 48px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .header {
      opacity: 0;
      transform: translateY(20px);
      animation: riseIn 0.7s 0.3s cubic-bezier(0.16, 1, 0.3, 1) forwards;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .logo-wrap {
      margin-bottom: 8px;
    }

    .logo {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: clamp(52px, 12vw, 84px);
      line-height: 0.92;
      letter-spacing: -0.03em;
      color: var(--text);
      display: inline-block;
    }

    .logo-underline {
      display: block;
      height: 2px;
      width: 0%;
      background: var(--accent);
      margin-top: 6px;
      transition: width 0.6s 1.2s cubic-bezier(0.16, 1, 0.3, 1);
    }

    body.loaded .logo-underline {
      width: 100%;
    }

    .tagline {
      font-size: 12px;
      letter-spacing: 0.08em;
      color: var(--muted);
      line-height: 1.6;
      margin-top: 18px;
      text-transform: uppercase;
    }

    .tagline span {
      color: var(--accent);
    }

    .divider {
      width: 100%;
      height: 1px;
      background: var(--line);
      margin: 32px 0;
      opacity: 0;
      animation: riseIn 0.5s 0.8s ease forwards;
    }

    .bottom {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      opacity: 0;
      animation: riseIn 0.5s 0.9s ease forwards;
    }

    .link {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 62px;
      height: 62px;
      border-radius: 10px;
      color: var(--muted);
      text-decoration: none;
      border: 1px solid transparent;
      transition: color 0.2s, border-color 0.2s, background 0.2s, transform 0.2s;
      position: relative;
      background: none;
      cursor: pointer;
      font-family: inherit;
    }

    .link:hover {
      color: var(--accent);
      border-color: var(--accent-glow);
      background: var(--accent-dim);
      transform: translateY(-3px);
    }

    .link.active {
      color: var(--accent);
      border-color: var(--accent-glow);
      background: var(--accent-dim);
    }

    .link svg {
      width: 32px;
      height: 32px;
      fill: currentColor;
      flex-shrink: 0;
    }

    .link::after {
      content: attr(data-label);
      position: absolute;
      bottom: calc(100% + 8px);
      left: 50%;
      transform: translateX(-50%) translateY(4px);
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: var(--accent);
      background: var(--surface);
      border: 1px solid var(--accent-glow);
      padding: 4px 8px;
      border-radius: 3px;
      white-space: nowrap;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.15s, transform 0.15s;
    }

    .link:hover::after {
      opacity: 1;
      transform: translateX(-50%) translateY(0);
    }

    .link-sep {
      width: 1px;
      height: 28px;
      background: var(--line);
      margin: 0 2px;
      flex-shrink: 0;
    }

    /* попover */
    #proj-panel {
      position: absolute;
      width: 300px;
      background: var(--surface);
      border: 1px solid var(--line2);
      border-radius: 12px;
      padding: 8px;
      z-index: 200;
      /* старт скрытый */
      opacity: 0;
      pointer-events: none;
      transform: translateY(4px) scale(0.97);
      transition: opacity 0.18s ease, transform 0.18s ease;
    }

    #proj-panel.open {
      opacity: 1;
      pointer-events: all;
      transform: translateY(0) scale(1);
    }

    .panel-label {
      font-size: 9px;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--muted);
      padding: 4px 10px 8px;
    }

    .project-item {
      display: flex;
      align-items: flex-start;
      gap: 12px;
      padding: 10px;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.15s;
    }

    .project-item:hover {
      background: var(--surface2);
    }

    .project-icon {
      width: 36px;
      height: 36px;
      border-radius: 8px;
      background: var(--surface2);
      border: 1px solid var(--line2);
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
      color: var(--muted);
      margin-top: 1px;
      transition: color 0.15s, border-color 0.15s, background 0.15s;
    }

    .project-item:hover .project-icon {
      color: var(--accent);
      border-color: var(--accent-glow);
      background: var(--accent-dim);
    }

    .project-icon svg {
      width: 18px;
      height: 18px;
      fill: currentColor;
    }

    .project-info {
      text-align: left;
      flex: 1;
      min-width: 0;
    }

    .project-name {
      font-size: 12px;
      color: var(--text);
      letter-spacing: 0.02em;
      line-height: 1.3;
    }

    .project-desc {
      font-size: 10px;
      color: var(--muted);
      letter-spacing: 0.02em;
      margin-top: 3px;
      line-height: 1.5;
    }

    .project-role {
      display: inline-block;
      font-size: 9px;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--accent);
      margin-top: 4px;
      background: var(--accent-dim);
      border: 1px solid var(--accent-glow);
      border-radius: 3px;
      padding: 1px 5px;
    }

    .panel-sep {
      height: 1px;
      background: var(--line);
      margin: 4px 10px;
    }

    @keyframes riseIn {
      to {
        opacity: 1;
        transform: none;
      }
    }

    @media (max-width: 480px) {
      .card {
        padding: 40px 24px 36px;
      }

      .corner {
        display: none;
      }

      .link {
        width: 54px;
        height: 54px;
      }

      .link svg {
        width: 28px;
        height: 28px;
      }

      .link::after {
        display: none;
      }

      #proj-panel {
        width: calc(100vw - 24px);
      }
    }
  </style>
</head>

<body>

  <div class="corner tl"></div>
  <div class="corner tr"></div>
  <div class="corner bl"></div>
  <div class="corner br"></div>

  <div class="card">
    <div class="header">
      <div class="logo-wrap">
        <div class="logo">seetch</div>
        <span class="logo-underline"></span>
      </div>
      <p class="tagline">
        люблю <span>java</span> · разрабатываю для <span>майнкрафт</span> и <span>телеграм</span>
      </p>
    </div>

    <div class="divider"></div>

    <div class="bottom">

      <a class="link" href="https://github.com/seetch" target="_blank" rel="noopener" data-label="github"
        aria-label="GitHub">
        <svg viewBox="0 0 24 24">
          <path
            d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12" />
        </svg>
      </a>

      <a class="link" href="https://t.me/seetche" target="_blank" rel="noopener" data-label="телеграм"
        aria-label="Telegram">
        <svg viewBox="0 0 24 24">
          <path
            d="M11.944 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0a12 12 0 0 0-.056 0zm4.962 7.224c.1-.002.321.023.465.14a.506.506 0 0 1 .171.325c.016.093.036.306.02.472-.18 1.898-.962 6.502-1.36 8.627-.168.9-.499 1.201-.82 1.23-.696.065-1.225-.46-1.9-.902-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.061 3.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635z" />
        </svg>
      </a>

      <a class="link" href="https://vk.com/seetch" target="_blank" rel="noopener" data-label="вконтакте"
        aria-label="ВКонтакте">
        <svg viewBox="0 0 24 24">
          <path
            d="M15.684 0H8.316C1.592 0 0 1.592 0 8.316v7.368C0 22.408 1.592 24 8.316 24h7.368C22.408 24 24 22.408 24 15.684V8.316C24 1.592 22.391 0 15.684 0zm3.692 17.123h-1.744c-.66 0-.864-.525-2.05-1.727-1.033-1-1.49-1.135-1.744-1.135-.356 0-.458.102-.458.593v1.575c0 .424-.135.678-1.253.678-1.846 0-3.896-1.118-5.335-3.202C4.624 10.857 4.03 8.57 4.03 8.096c0-.254.102-.491.593-.491h1.744c.44 0 .61.203.78.677.863 2.49 2.303 4.675 2.896 4.675.22 0 .322-.102.322-.66V9.721c-.068-1.186-.695-1.287-.695-1.71 0-.203.17-.407.44-.407h2.744c.373 0 .508.203.508.643v3.473c0 .372.17.508.271.508.22 0 .407-.136.813-.542 1.253-1.406 2.151-3.574 2.151-3.574.119-.254.322-.491.762-.491h1.744c.525 0 .644.27.525.643-.22 1.017-2.354 4.031-2.354 4.031-.186.305-.254.44 0 .78.186.254.796.779 1.203 1.253.745.847 1.32 1.558 1.473 2.05.17.49-.085.744-.576.744z" />
        </svg>
      </a>

      <div class="link-sep"></div>

      <a class="link" href="https://repo.seetch.ru" target="_blank" rel="noopener" data-label="maven"
        aria-label="Maven">
        <svg viewBox="0 0 24 24">
          <path
            d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm0 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12 6.477 2 12 2zm-.5 3v6.268l-4.5-2.598-.5.866 5 2.887V19h1v-6.577l5-2.887-.5-.866-4.5 2.598V5h-1z" />
        </svg>
      </a>

      <div class="link-sep"></div>

      <button class="link" id="proj-btn" data-label="проекты" aria-label="Проекты">
        <svg viewBox="0 0 24 24">
          <path fill="currentColor" d="M3 3h8v8H3zm0 10h8v8H3zM13 3h8v8h-8zm0 10h8v8h-8z" />
        </svg>
      </button>

    </div>
  </div>

  <div id="proj-panel">
    <div class="panel-label">проекты</div>

    <a class="project-item" href="https://t.me/daycube" target="_blank" rel="noopener">
      <div class="project-icon">
        <svg viewBox="0 0 24 24">
          <path
            d="M20 3H4a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zm-1 4H5V5h14v2zm0 3H5a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1zm-1 4H6v-2h12v2zm1 3H5a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1zm-1 2H6v-1h12v1z" />
        </svg>
      </div>
      <div class="project-info">
        <div class="project-name">DAYCUBE</div>
        <div class="project-desc">Анархия Minecraft</div>
        <div class="project-role">владелец · разработчик</div>
      </div>
    </a>

    <a class="project-item" href="https://t.me/cubehead_news" target="_blank" rel="noopener">
      <div class="project-icon">
        <svg viewBox="0 0 24 24">
          <path
            d="M20 3H4a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zm-1 4H5V5h14v2zm0 3H5a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1zm-1 4H6v-2h12v2zm1 3H5a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1zm-1 2H6v-1h12v1z" />
        </svg>
      </div>
      <div class="project-info">
        <div class="project-name">CUBE HEAD</div>
        <div class="project-desc">Анархия Minecraft</div>
        <div class="project-role">разработчик</div>
      </div>
    </a>

    <div class="panel-sep"></div>

    <a class="project-item" href="https://t.me/rpfresh" target="_blank" rel="noopener">
      <div class="project-icon">
        <svg viewBox="0 0 24 24">
          <path
            d="M11.944 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0a12 12 0 0 0-.056 0zm4.962 7.224c.1-.002.321.023.465.14a.506.506 0 0 1 .171.325c.016.093.036.306.02.472-.18 1.898-.962 6.502-1.36 8.627-.168.9-.499 1.201-.82 1.23-.696.065-1.225-.46-1.9-.902-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.061 3.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635z" />
        </svg>
      </div>
      <div class="project-info">
        <div class="project-name">Fresh</div>
        <div class="project-desc">Ресурспаки для Minecraft: Bedrock</div>
        <div class="project-role">автор</div>
      </div>
    </a>

    <div class="panel-sep"></div>

    <a class="project-item" href="https://t.me/rpfreshbot" target="_blank" rel="noopener">
      <div class="project-icon">
        <svg viewBox="0 0 24 24">
          <path
            d="M12 2a2 2 0 0 1 2 2c0 .74-.4 1.39-1 1.73V7h1a7 7 0 0 1 7 7H3a7 7 0 0 1 7-7h1V5.73c-.6-.34-1-.99-1-1.73a2 2 0 0 1 2-2zM7.5 14a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zm9 0a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zM2 17l1.5 5h17L22 17H2z" />
        </svg>
      </div>
      <div class="project-info">
        <div class="project-name">Fresh Bot</div>
        <div class="project-desc">3D тотемы для Minecraft: Bedrock</div>
        <div class="project-role">разработчик</div>
      </div>
    </a>
  </div>

  <script type="module">
    import { computePosition, flip, shift, offset, autoUpdate } from 'https://cdn.jsdelivr.net/npm/@floating-ui/dom@1.6.10/+esm';

    const btn = document.getElementById('proj-btn');
    const panel = document.getElementById('proj-panel');
    let cleanup = null;

    function updatePosition() {
      computePosition(btn, panel, {
        placement: 'top',
        middleware: [
          offset(10),
          flip(),
          shift({ padding: 12 }),
        ],
      }).then(({ x, y }) => {
        Object.assign(panel.style, { left: x + 'px', top: y + 'px' });
      });
    }

    function open() {
      panel.classList.add('open');
      btn.classList.add('active');
      cleanup = autoUpdate(btn, panel, updatePosition);
    }

    function close() {
      panel.classList.remove('open');
      btn.classList.remove('active');
      if (cleanup) { cleanup(); cleanup = null; }
    }

    btn.addEventListener('click', (e) => {
      e.stopPropagation();
      panel.classList.contains('open') ? close() : open();
    });

    document.addEventListener('click', (e) => {
      if (!panel.contains(e.target) && e.target !== btn) close();
    });

    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape') close();
    });
  </script>

  <script>
    window.addEventListener('load', () => {
      setTimeout(() => document.body.classList.add('loaded'), 100);
    });
  </script>
</body>

</html>
