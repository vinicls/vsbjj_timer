<div align="center">

<img src="logo_vsbjj_nobg_shad_resized.png" alt="VS BJJ" width="220">

# VS BJJ Timer

**Coach Victor Simões · Oakville, ON, Canada**

*Training timer built exclusively for VS BJJ academy · Timer de treino desenvolvido exclusivamente para a academia VS BJJ*

![Version](https://img.shields.io/badge/version-v3.10-D85A30?style=flat-square) ![PWA](https://img.shields.io/badge/PWA-ready-1D9E75?style=flat-square) ![Platform](https://img.shields.io/badge/platform-TV%20%7C%20tablet%20%7C%20mobile-185FA5?style=flat-square) ![Offline](https://img.shields.io/badge/offline-capable-888888?style=flat-square)

</div>

---

## 🇨🇦 English (Canada)

### What is it?

**VS BJJ Timer** is a professional training timer developed exclusively for **VS BJJ**, Coach Victor Simões's academy in **Oakville, Ontario, Canada**. It runs directly in any web browser — no installation required, no sign-up, no mandatory internet connection — and works on TVs, computers, tablets, and smartphones.

---

### Who is it for?

- **Coaches** — full control of training sessions on the academy TV or a tablet at mat-side
- **Students** — access via smartphone to track time during free sparring
- **Internal referees** — use during in-house tournaments and selection events

---

### Features

#### ⏱ Round Timer
Automatically tracks fight and rest time in sequence. When a round ends, rest begins automatically; when rest ends, the next round starts with an audio cue — no manual intervention required.

#### ⚙️ Full Configuration
- Round duration: 1 to 60 minutes
- Rest time: 10s, 15s, 30s, 1min, 1min 30s, 2min, or 3min
- Number of rounds: 1 to 20
- Warning beep: configurable seconds before round ends

#### ⚡ Quick Presets

Six pre-configured settings for the most common training scenarios:

| Preset | Round | Rest | Rounds |
|---|---|---|---|
| Test / Warm-up | 1 min | 10s | 2 |
| Kids | 2 min | 1 min | 3 |
| Youth | 4 min | 1 min | 3 |
| Adult (Competition) | 5 min | 30s | 5 |
| Master | 5 min | 1 min | 3 |
| Training | 5 min | 1 min 30s | 3 |

#### 🔔 Smart Alerts
- **Get Ready Alert** — beeps 5 seconds before the first round, giving athletes time to get in position
- **Next Round Alert** — beeps during the last 10 seconds of rest, signalling the next round is coming

#### 👁 Visual Indicators
- Large, TV-readable numbers
- Smooth 60fps progress bar — no jumps or skips
- Animated dots showing completed and active rounds
- Colour-coded phase pill: *Ready / Get Ready / Fight / Rest / Done*
- Amber warning colour during readiness alerts; red during final seconds of a round
- Pulse effect on the START button — subtle breathing animation when idle

#### 📺 Clean Execution Screen
When the timer starts, the configuration panel slides away and the timer fills the entire screen — optimized for TV display. The clock in 12h AM/PM format remains visible in the top-left corner on desktop and tablet.

#### 🌗 Light & Dark Mode
Toggle between Light and Dark themes. Dark Mode is recommended for TV use in dimly lit gyms.

#### 🌙 Screensaver
After 5 minutes of inactivity on desktop/TV, the VS BJJ logo appears centred on a dark overlay with a gentle breathing animation — indicating the app is active and ready. Any tap, click, or key press dismisses it.

#### 🔊 Professional Audio
Audio generated via the Web Audio API — no external files required. Three distinct sounds: round start (sharp, energetic tone), round end (deep closing tone), and warning beeps (rhythmic pulses).

#### 📱 PWA — Installs as an App
Can be added to the home screen of iPhone and Android devices. Runs fullscreen without the browser bar, like a native app. Displays the VS BJJ icon on a cream background.

#### 💡 Wake Lock
Keeps the screen on while the timer is running — the display won't auto-lock during training.

#### 📐 Fully Responsive
- **TV / Desktop** — two-column layout optimized for distance viewing
- **Tablet** — adapted layout in portrait and landscape
- **Smartphone** — compact layout in both portrait and landscape, with clock hidden on execution screen (system clock already visible in status bar)
- Works offline after the first load

---

### Files

| File | Description |
|---|---|
| `index.html` | Main app — single file, no dependencies |
| `manifest.json` | PWA manifest for Android installation |
| `logo_vsbjj_nobg_shad_resized.png` | Academy logo (PNG with transparency) |

> All three files must be in the same folder.

---

### Identity

Built with the **VS BJJ** visual identity — custom colours, logo, and footer. A periodic shimmer effect on the logo reinforces brand presence throughout training.

> **VS BJJ · Coach Victor Simões · Oakville, ON, Canada · Timer v3.10**

---
---

## 🇧🇷 Português (Brasil)

### O que é?

O **VS BJJ Timer** é um cronômetro profissional de treino desenvolvido exclusivamente para a academia **VS BJJ** do **Coach Victor Simões**, em **Oakville, Ontario, Canadá**. Funciona diretamente no navegador — sem instalação, sem cadastro, sem internet obrigatória — e pode ser usado em TVs, computadores, tablets e celulares.

---

### Para quem é?

- **Professores** — controle total do treino na TV da academia ou no tablet à beira do tatame
- **Alunos** — acesso pelo celular para acompanhar o tempo durante sparrings livres
- **Árbitros internos** — uso em campeonatos e seletivas da academia

---

### Funcionalidades

#### ⏱ Cronômetro de Rounds
Conta o tempo de luta e descanso em sequência automática. Ao final de cada round, o descanso começa automaticamente; ao final do descanso, o próximo round inicia com aviso sonoro — sem intervenção manual.

#### ⚙️ Configuração Completa
- Duração do round: 1 a 60 minutos
- Tempo de descanso: 10s, 15s, 30s, 1min, 1min30, 2min ou 3min
- Número de rounds: 1 a 20
- Aviso sonoro: segundos configuráveis antes do fim do round

#### ⚡ Presets Rápidos

Seis configurações pré-definidas para os cenários de treino mais comuns:

| Preset | Round | Descanso | Rounds |
|---|---|---|---|
| Teste / Aquecimento | 1 min | 10s | 2 |
| Kids | 2 min | 1 min | 3 |
| Juvenil | 4 min | 1 min | 3 |
| Adulto (Competição) | 5 min | 30s | 5 |
| Master | 5 min | 1 min | 3 |
| Treino Livre | 5 min | 1 min 30s | 3 |

#### 🔔 Alertas Inteligentes
- **Get Ready Alert** — beeps 5 segundos antes do primeiro round, dando tempo para os atletas se posicionarem
- **Next Round Alert** — beeps nos últimos 10 segundos do descanso, sinalizando que o próximo round está próximo

#### 👁 Indicadores Visuais
- Números grandes e legíveis à distância em TVs
- Barra de progresso fluida a 60fps — sem saltos ou interrupções
- Dots animados mostrando rounds completos e em andamento
- Pill de fase colorida: *Ready / Get Ready / Fight / Rest / Done*
- Cor âmbar nos avisos de prontidão; vermelho nos segundos finais do round
- Efeito pulse no botão START — animação suave de respiração quando em repouso

#### 📺 Tela de Execução Limpa
Ao iniciar o timer, o painel de configurações some e o cronômetro ocupa a tela inteira — ideal para TV. O relógio em formato 12h AM/PM permanece visível no canto superior esquerdo em desktop e tablet.

#### 🌗 Modo Claro e Escuro
Toggle entre Light Mode e Dark Mode. O Dark Mode é recomendado para uso em TV em ambientes com pouca luz.

#### 🌙 Descanso de Tela
Após 5 minutos de inatividade em desktop/TV, a logo da VS BJJ aparece centralizada em overlay escuro com animação suave — indica que o app está ativo e pronto. Qualquer toque, clique ou tecla dispensa o descanso de tela.

#### 🔊 Áudio Profissional
Áudio gerado via Web Audio API — sem arquivos externos. Três sons distintos: início de round (tom agudo e energético), fim de round (tom grave de encerramento) e beeps de aviso (pulsos rítmicos).

#### 📱 PWA — Instala como App
Pode ser adicionado à tela inicial do iPhone e Android. Funciona em tela cheia, sem barra do navegador, como um app nativo. Exibe o ícone da VS BJJ com fundo creme.

#### 💡 Wake Lock
Mantém a tela ativa enquanto o timer está rodando — a tela não bloqueia automaticamente durante o treino.

#### 📐 Totalmente Responsivo
- **TV / Desktop** — layout de duas colunas otimizado para visualização à distância
- **Tablet** — layout adaptado em modo retrato e paisagem
- **Celular** — layout compacto em retrato e paisagem, com relógio oculto na tela de execução (o relógio do sistema já aparece na barra de status)
- Funciona offline após o primeiro carregamento

---

### Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | App principal — arquivo único, sem dependências |
| `manifest.json` | Manifest PWA para instalação no Android |
| `logo_vsbjj_nobg_shad_resized.png` | Logo da academia (PNG com transparência) |

> Os três arquivos devem estar na mesma pasta.

---

### Identidade

Desenvolvido com a identidade visual da **VS BJJ** — cores, logo e rodapé personalizados. O efeito de shimmer periódico na logo reforça a presença da marca durante o treino.

> **VS BJJ · Coach Victor Simões · Oakville, ON, Canada · Timer v3.10**
