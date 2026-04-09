# Rogue like Deck Building Simple Chess Game   

https://yeohs0212.github.io/chess-roguelike/


# ♟️ Chess Roguelike

**Deckbuilding × Chess × Roguelike**
A web-based, turn-based strategy game that combines the tactical movement of chess with the deckbuilding mechanics of card games and the randomized reward systems of a roguelike.

<br>

## 📜 How to Play

1. **Win Condition:** Survive across 10 stages and checkmate the enemy king.
2. **Action Points (AP):** You are given **1 AP** per turn. You can spend AP to either **move** a piece on the board or **place (summon)** a card from your hand onto an empty square near your King.
3. **Draw:** Every time you capture an enemy piece, you draw 1 card from your deck.
4. **Stalemate:** Following standard chess rules, if a player has no legal moves but is not in check (stalemate), the player who is trapped loses. If you trap the enemy, you lose. However, if the enemy traps you, it counts as a stage clear!

<br>

## ✨ Core Features

### 🃏 Deckbuilding & Card Placement
* Chess pieces exist as cards in your deck (Pawn, Knight, Bishop, Rook, Queen).
* Consume cards to freely summon allied pieces within a designated range around your King.
* Includes traditional deckbuilding elements like deck compression (permanently removing cards from the graveyard) and graveyard reshuffling.

### ⚔️ Piece Upgrades
* Collect **3 copies** of the same common card to permanently upgrade them into a piece with special abilities.
* **Upgrade Examples:**
  * `Elite Pawn (♙★)`: Basic pawn movement + can move 1 square diagonally.
  * `Rampage Rook (♖⚡)`: Charges through its movement path, eliminating all enemy pieces in its way.
  * `Twin Bishop (♗♗)`: Can move on both light and dark squares (gains linear movement like a Rook).

### 🎁 Roguelike Rewards & Rarity
* Choose 1 of 3 randomized rewards upon clearing a stage to grow your party.
* Rewards feature different tiers ranging from **Common to Legendary**.
* Beyond acquiring new cards, you can permanently buff your King's stats (e.g., increased summon range, increased movement range, or a shield that nullifies one checkmate).

### 🤖 Dynamic Difficulty AI
* Features an enemy AI powered by the **Minimax algorithm (+Alpha-Beta Pruning)**.
* Calculates optimal moves using Piece-Square Tables (PST) and piece values.
* The AI's calculation depth scales from 2 to 5 as you progress through the stages, becoming progressively smarter and more challenging.

<br>

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Zero Dependencies:** Runs lightning fast as a single HTML file without any heavy frameworks or external libraries.
* **Deployment:** GitHub Pages

<br>

## 👨‍💻 Developer
* **Created by:** yeohs0212

# ♟️ Chess Roguelike (체스 로그라이크)

**덱빌딩(Deckbuilding) × 체스(Chess) × 로그라이크(Roguelike)**
체스의 전략적인 움직임에 카드 게임의 덱빌딩, 그리고 로그라이크의 무작위 보상 시스템을 결합한 웹 기반 턴제 전략 게임입니다.

<br>

## 📜 게임 규칙 (How to Play)

1. **승리 목표:** 총 10개의 스테이지에서 적의 킹을 잡고(체크메이트) 살아남아야 합니다.
2. **행동력 (AP):** 내 턴에는 기본적으로 **1의 행동력**이 주어집니다. 행동력을 소비하여 보드 위의 기물을 **이동**하거나, 손패에 있는 카드를 킹 주변 빈 공간에 **배치(소환)**할 수 있습니다.
3. **드로우:** 적의 기물을 포획(처치)할 때마다 덱에서 카드를 1장 뽑습니다.
4. **스테일메이트:** 체스 룰과 동일하게, 어느 한 쪽이 움직일 기물이 없는데 체크 상태가 아니라면(스테일메이트) 묶인 쪽이 패배합니다. 적을 묶으면 내가 지고, 적이 나를 묶으면 클리어로 인정됩니다!

<br>

## ✨ 핵심 기능 (Features)

### 🃏 덱빌딩 & 카드 배치 시스템
* 체스 기물들이 카드로 존재합니다. (폰, 나이트, 비숍, 룩, 퀸)
* 카드를 소모해 킹 주변의 지정된 범위 내에 아군 기물을 자유롭게 배치할 수 있습니다.
* 덱 압축(묘지 영구 제거), 묘지 리셔플 등 정통 덱빌딩 요소를 포함합니다.

### ⚔️ 기물 강화 (업그레이드)
* 동일한 일반 등급의 카드 **3장**을 모으면, 특별한 능력을 지닌 기물로 영구 강화할 수 있습니다.
* **강화 예시:** * `정예폰(♙★)`: 기본 폰 이동 + 대각선 1칸 추가 이동
  * `돌진룩(♖⚡)`: 이동 경로에 있는 적 기물도 통과하며 모두 제거
  * `쌍둥이주교(♗♗)`: 두 색상의 칸 모두 이동 가능 (직선 이동 추가)

### 🎁 로그라이크 보상 & 희귀도
* 스테이지 클리어 시 3가지 무작위 보상 중 하나를 선택해 파티를 성장시킵니다.
* 보상에는 **일반(Common) ~ 전설(Legendary)** 등급이 존재합니다.
* 카드 추가 획득뿐만 아니라 킹의 능력치(소환 범위 증가, 이동 보폭 증가, 체크메이트 1회 무효화 방어막)를 영구적으로 올릴 수 있습니다.

### 🤖 동적 난이도 AI
* **Minimax 알고리즘 (+Alpha-Beta Pruning)** 기반의 적 AI가 탑재되어 있습니다.
* 각 기물의 가치와 위치 점수(Piece-Square Tables)를 계산하여 최적의 수를 둡니다.
* 스테이지가 올라갈수록 AI가 계산하는 깊이(Depth)가 2에서 5까지 증가하여 점점 더 영리해집니다.

<br>

## 🛠️ 기술 스택 (Tech Stack)

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **No Frameworks:** 무거운 라이브러리나 프레임워크 없이 단일 HTML 파일로 가볍고 빠르게 동작합니다.
* **Deployment:** GitHub Pages

<br>

## 👨‍💻 제작자
* **Developer:** yeohs0212
