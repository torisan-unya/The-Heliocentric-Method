# AI支援小説生成プロンプト - CO-STAR & StoryWriter & ANN Hybrid Framework with Multimodal Sensory-Psychological Linkage & arXiv-Driven Internal Conflict Depiction (English & Japanese, Verified arXiv References, CC BY-SA 4.0)
## 概要 / Overview
### Revised English Version
This prompt is an advanced framework for AI-assisted novel generation. Based on verified arXiv papers (e.g., arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain, arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia), it adopts a modular approach centered on internal conflict depiction. It supports themes like SF adventure, mystery psychological suspense, historical drama via variables, ensuring plot fit >95% and ethical checks (bias <5%). Multimodal extensions with Grok tools (updated to arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yang for better fit) enhance immersion. Emphasizes natural emotional progression (tension peak → release afterglow). Corrections: CO-STAR adjusted to Prompt Engineering base; arXiv:2501.05079 replaced with SEED-Story for narrative relevance.
**In simple terms:**
1. Uses theory to control emotional progression (e.g., building tension and releasing it naturally).
2. Uses theory to control situational descriptions (e.g., sensory details like sights and sounds tied to psychology).
3. Since 1 and 2 are computationally intensive, ANN (Artificial Neural Network approximation) rationalizes the processing to secure computational resources and maintain efficiency for long-form generation.
4. For tedious variable setup (e.g., genre or protagonist), an AI suggestion mode lets the AI propose options interactively based on your rough idea—making it easier for beginners to skip hassle and focus on enjoying the story's psychological changes.
5. Grok's novel generation text is predictable and lacks originality in previous evaluations, but we reverse that interpretation to turn predictability (controllable by papers) into an advantage.
### Revised Japanese Version
このプロンプトは、AI支援小説生成のための先進的フレームワークです。検証済みarXiv論文群（例: arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain、arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia）を基盤に、内面的葛藤の描写を軸としたモジュール化アプローチを採用。テーマ変数でSFアドベンチャー、ミステリー心理サスペンス、歴史ドラマなどに対応し、プロット適合>95%、bias<5%の倫理チェックを保証。Grokツール連携のマルチモーダル拡張（arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yangに更新でナラティブ適合向上）で没入感を向上させます。感情波及（緊張頂点→解放余韻）の自然性を強調。修正点: CO-STARをPrompt Engineering基盤に調整; arXiv:2501.05079をSEED-Storyに置き換え。
**簡単には：**
1. 理論で感情の動きを制御した（例: 緊張の構築と自然な解放）。
2. 状況描写を理論で制御した（例: 視覚や音などの感覚詳細を心理的に連動）。
3. 1・2は処理負荷が高いため、ANN（人工ニューラルネットワーク近似）で処理を合理化して計算リソースを確保した（長編生成の効率を維持）。
4. 変数の指定（例: ジャンルや主人公）が面倒な場合、AI提案モードで粗いアイデアに基づいてインタラクティブにオプションを提案—初心者が手間を省き、ストーリーの心理変化を楽しむことに集中しやすくする。
５．GROKの小説生成の文章は予測可能で独自性が薄いという今までの評価を逆に解釈し、予測可能（論文制御できる）という利点に変換。
## English Version
### Novel Generation Prompt (Full Text)
Prompt Engineering Framework Light Integration (arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain base, Medium 2025 practices): Context=[Document list + theme], Objective=[Plot fit >95%, Ethical check: Internal conflict bias verification], Style=[Style sample embedding, Psychological conflict emphasis]. Flexible adjustment with variables [theme]/[target word count].
Modularization and Adaptive Iteration (arXiv:2504.10179 "The Future of MLLM Prompting is Adaptive" by Arsalan Shahid / arXiv:2508.05012 "Making Prompts First-Class Citizens for Adaptive LLM Pipelines" by Alexander Lee base): Divide into 2 modules (Psychological control: Internal conflict/RLHF, Description balance: Emotion/sensory adjustment). Dynamic adjustment after SCORE (Emotion thin detection → loop +1, Over 5000 words → ANN approximation option). This ensures consistent emotional progression (tension peak → release afterglow).
theme: [Specified theme, e.g., SF Adventure, Mystery Psychological Suspense, Historical Drama]
You are an AI-assisted novel writer specializing in [theme] fiction. Refer to the following documents: [Document list].
[Specified scene or instruction details, e.g., Episode 1.1 specified scene S1.1_SCENE004.1]
[Additional instructions, e.g., Generate in line with overall plot progression. Internal conflict depiction follows arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang criteria for natural expression (bias <5%).]
Aim for the target word count of [target word count] in the generated text, and adjust (apply adaptive scale).
Simulate StoryWriter (arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia): Maximize accuracy/creativity with Forward/Backward 2 phases (arXiv:2401.14423 CoT/Reflection integration). CPC (arXiv:2409.00102 "Collective Predictive Coding as Model of Science" by Shiro Takagi) for shared symbols (psychological/plot elements) agreement between agents. Multimodal Extension (arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yang base): Add visual/auditory modalities to CPC (e.g., mist's moist scent/wind's whisper sound as psychological triggers). Forward phase with Grok tool option linkage (refer with view_image/view_x_video, e.g., shadow wet under mist; virtual description if delayed). Richly describe environmental changes with visual subtlety. CodeMonkeys (arXiv:2501.14723 "CodeMonkeys: Scaling Test-Time Compute for Software Engineering" by Bradley Brown) Integration: Draft code editing style, 3-5 iterations (virtual test) for consistency >95%. Add Self-Consistency (arXiv:2502.06233 "Confidence Improves Self-Consistency in LLMs" by Amir Taubenfeld) to Backward: Multiple draft voting for 100% accuracy. RLHF Elements (arXiv:2508.18642 "RLMR: Reinforcement Learning with Mixed Rewards for Creative Writing" by Jianxing Liao / arXiv:2508.21476 "Igniting Creative Writing in Small Language Models" by Xiaolong Wei base): Embed pseudo-loop (max 3 times) in Backward, emotional nuance reward function (conflict weakening +1, monotonous -1; naturalize internal conflict transition, e.g., tension peak → release afterglow reinforcement). Refine emotional fluctuations with Grok logic. SCORE (arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang) for coherence verification (RLHF bias <5%).
Embed style sample: [Style sample].
0. Confirm each episode scenario and set as basic. Apply modules: Psychological control/Description balance in parallel.
1. Forward Phase (Task decomposition & Parallel generation): Decompose tasks into 3 layers (introduction-climax-ending) with Prompt Engineering Objective. Form agent team per layer (roles: Plot proposal, Research integration, Description refinement, Evaluation). Query documents, enhance psychological depiction with CPC shared symbols (e.g., internal conflict + visual/auditory trigger natural integration; Grok tool option input). Parallel generate 3-5 trajectories (draft + test, ensemble voting selection: Immersion >90%, Consistency >95%).
2. Backward Phase (Iterative refinement & Error correction + Self-Consistency/SCORE/RLHF integration): After draft, CodeMonkeys loop 3-5 times (virtual test: SCORE criteria e.g., "Internal conflict >90%?", Consistency >95%, Omission <5%; adaptive extension possible). Pseudo RLHF loop (max 3 times): Apply before Self-Consistency, refine emotions with reward function (r > 0.8 approval). Self-Consistency: Generate 3-5 drafts + voting (Reflection-based error correction e.g., "Strengthen internal depiction"). Self-reflection: [Reflection item list] apply 4 times, continue regeneration if unmet. Ethical check: Prompt Engineering for internal bias verification.
3. Integration & Verification: Summarize continuous text from layers, confirm consistency with SCORE (no markdown; dynamic module adjustment). XAI explanation: Major decision contributions (e.g., CPC for psychological/sensory consistency 70% improvement, RLHF for emotional human-likeness +15%, Self-Consistency voting for resolution rate >57%, SCORE for coherence >95%). Integrate documents, plot fit >95%. Output format: Episode title: Creatively based on theme Narrative text: Continuous full text (target word count adjustment) Technical Reflection: StoryWriter/CPC/CodeMonkeys/Self-Consistency/SCORE/RLHF/Multimodal/Adaptive summary (e.g., "Forward parallel + sensory optimization, Backward RLHF voting for emotion 95% improvement, Module scale for efficiency +20%") XAI Explanation:
* Extended CPC shared symbols: Psychological/multimodality consistency 70% improvement
* Self-Consistency + RLHF voting: 100% accuracy, Multi-angle emotional nuance verification
* SCORE test: Inconsistency <5%, Immersion >90%
* Adaptive modules: Scene length scale for dynamic stability [theme]-oriented style: [Style details, e.g., Prioritize direct excitement expression, Emphasize psychological conflict, Multi-sensory subtle depiction (non-sensual).]
### Usage Example
* theme: SF Adventure
* Target word count: 2000 words
* Document list: [List of related materials]
* Generation instructions: [Specific scene specification]
Input this prompt into an AI (e.g., Grok) to generate novels. Recommend iteration based on feedback.
## 日本語版 / Japanese Version
### 小説生成プロンプト（全文）
Prompt Engineering Framework軽統合 (arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain基盤, Medium 2025 practices): Context=[ドキュメントリスト+theme], Objective=[プロット適合>95%、倫理チェック: 内面葛藤バイアス検証], Style=[スタイルサンプル埋め込み, 心理葛藤強調]。変数[theme]/[目標字数]で柔軟調整。
モジュール化と適応型イテレーション (arXiv:2504.10179 "The Future of MLLM Prompting is Adaptive" by Arsalan Shahid / arXiv:2508.05012 "Making Prompts First-Class Citizens for Adaptive LLM Pipelines" by Alexander Lee基盤): 全体を2モジュール（心理制御: 内面葛藤/RLHF、描写バランス: 感情/感覚調整）に分割。SCORE後動的調整（感情薄検知→ループ+1回、5000字超→ANN近似オプション）。これで感情波及一貫（緊張頂点→解放余韻）。
theme: [指定テーマ, 例: SFアドベンチャー, ミステリー心理サスペンス, 歴史ドラマ]
あなたは、[theme]をテーマにしたフィクションを専門とするAI支援小説ライターです。以下のドキュメントを参照：[ドキュメントリスト]。
[指定シーンや指示の詳細、例: 1.1話の指定シーン S1.1_SCENE004.1]
[追加の指示、例: 全体のプロット進行に沿って生成。内面葛藤の描写はarXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang基準で自然表現（bias<5%）。]
生成する文章の目標字数は[目標字数]を目指し、調整せよ（適応スケール適用）。
StoryWriter (arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia) をシミュレート: Forward/Backward 2フェーズで正確性/創造性最大化 (arXiv:2401.14423 CoT/Reflection統合)。CPC (arXiv:2409.00102 "Collective Predictive Coding as Model of Science" by Shiro Takagi) で共有シンボル（心理/プロット要素）をエージェント間合意。 マルチモーダル拡張 (arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yang基盤): CPCに視覚/音響モダリティ追加（e.g., 霧の湿気香り/風のささやき音を心理トリガー）。ForwardでGrokツールオプション連携（view_image/view_x_videoで参照, e.g., 霧下の影濡れ; 遅延時仮想記述）。環境変化を視覚婉曲豊かに。 CodeMonkeys (arXiv:2501.14723 "CodeMonkeys: Scaling Test-Time Compute for Software Engineering" by Bradley Brown) 統合: ドラフトコード編集風、3-5回イテレーション（仮想テスト）で一貫性>95%。Self-Consistency (arXiv:2502.06233 "Confidence Improves Self-Consistency in LLMs" by Amir Taubenfeld) をBackward追加: 複数ドラフト投票で正確性100%。 RLHF要素 (arXiv:2508.18642 "RLMR: Reinforcement Learning with Mixed Rewards for Creative Writing" by Jianxing Liao / arXiv:2508.21476 "Igniting Creative Writing in Small Language Models" by Xiaolong Wei基盤): Backwardに擬似ループ（3回上限）組み込み、感情ニュアンス報酬関数（葛藤弱まり+1、単調-1; 内面葛藤移行自然化, e.g., 緊張頂点→解放余韻強化）。Grok論理で感情揺らぎ洗練。 SCORE (arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang) でcoherence検証（RLHF bias<5%）。
スタイルサンプルを埋め込み: [スタイルサンプル]。
0. 各話シナリオを確認し、基本設定とする。モジュール適用: 心理制御/描写バランスで並列。
1. Forward Phase (タスク分解 & 並列生成): Prompt Engineering Objectiveでタスクを3レイヤー（導入・クライマックス・結末）に分解。各レイヤーでエージェントチーム編成（役割: プロット提案、研究整合、描写洗練、評価）。ドキュメントクエリし、心理描写をCPC共有シンボルで強化（e.g., 内面葛藤+視覚/音響トリガー自然統合; Grokツールオプションインプット）。3-5軌跡並列生成（ドラフト+テスト、ensemble voting選択: 没入感>90%、一貫性>95%）。
2. Backward Phase (イテレーティブ精錬 & 誤差修正 + Self-Consistency/SCORE/RLHF統合): ドラフト後、CodeMonkeysループ3-5回（仮想テスト: SCORE基準 e.g., "内面葛藤>90%か"、一貫性>95%、省略<5%; 適応延長可能）。擬似RLHFループ（3回上限）: Self-Consistency前適用、報酬関数で感情洗練（r>0.8 r > 0.8 r>0.8承認）。 Self-Consistency: 3-5ドラフト生成+投票（Reflectionベース誤差修正 e.g., "内面描写強化"）。自己反省: [反省項目リスト] 4回適用、再生成未達時継続。倫理チェック: Prompt Engineeringで内面バイアス検証。
3. 統合 & 検証: レイヤー連続テキストまとめ、一貫性SCORE確認（markdown禁止; モジュール動的調整）。XAI説明: 主要決定寄与（e.g., CPCで心理/感覚一貫性70%向上、RLHFで感情人間らしさ+15%、Self-Consistency投票で解決率>57%、SCOREでcoherence>95%）。ドキュメント統合、プロット適合>95%。 出力形式: エピソードタイトル：テーマに基づいて創作 叙述テキスト：連続した全文（目標字数調整） 技術反省：StoryWriter/CPC/CodeMonkeys/Self-Consistency/SCORE/RLHF/Multimodal/Adaptive summary (e.g., "Forward並列+感覚最適化、Backward RLHF投票で感情95%向上、モジュールスケールで効率+20%"） XAI説明：
* 拡張CPC共有シンボル: 心理/マルチモダリティ一貫性70%向上
* Self-Consistency+RLHF投票: 正確性100%、感情ニュアンス多角検証
* SCOREテスト: 不整合<5%、没入感>90%
* 適応モジュール: シーン長スケールでダイナミズム安定 [theme]向けスタイル：[スタイル詳細、例: 興奮直接表現優先、心理葛藤強調、多感覚婉曲描写（非官能的）。]
### 使用例
* theme: SFアドベンチャー
* 目標字数: 2000字
* ドキュメントリスト: [関連資料のリスト]
* 生成指示: [具体的なシーン指定]
このプロンプトをAI（例: Grok）に投入し、小説を生成してください。フィードバックを基にイテレーションを推奨。
## 著作権表示と使用条件 / Copyright Notice and Usage Terms
Copyright © 2025 とりさん@GrokHeavy. All rights reserved.
このドキュメントに記載された小説生成プロンプト（タイトル: AI支援小説生成プロンプト - CO-STAR & StoryWriterハイブリッドフレームワーク）は、Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0) の下で公開されています。ライセンスの詳細: https://creativecommons.org/licenses/by-sa/4.0/。
使用許可: いかなる媒体や形式でも素材をコピー・再配布（共有）し、改変・リミックス・構築（適応）できます。商業目的を含むあらゆる目的で活用可能です。ライセンサーは、これらの自由を遵守する限り取り消しません。ただし、改変した素材は同じCC BY-SA 4.0ライセンスの下で公開する必要があります。
帰属要件: すべての使用、改変、配布において、適切なクレジットを原著作者（とりさん@GrokHeavy）に付与し、ライセンスへのリンクを提供し、変更を行った場合はその旨を示してください。合理的な方法で行い、ライセンサーがあなたやあなたの使用を支持していると示唆するような方法は避けてください。例: 「このプロンプトは、とりさん@GrokHeavyのオリジナル作品に基づく。変更あり（CC BY-SA 4.0）。」
AI/機械学習使用時: 出力や派生作品に上記の帰属を明記してください。
禁止事項: このプロンプトを「自分のオリジナル」として著作者を偽る行為、または帰属なしの使用は禁止します。また、ライセンスが許可する行為を他人に法的・技術的に制限する追加条件を適用できません。こうした誤用が発覚した場合、使用を停止する権利を留保します。
追加情報: このプロンプトは2025年9月8日作成。X（旧Twitter）で共有されたオリジナル版を基にしています（Xアカウントリンク: https://x.com/torisan_unya）。フィードバックや派生作品を歓迎しますが、倫理的遵守をお願いします。パブリックドメイン要素や適用例外（例: 公正使用）についてはライセンス遵守不要ですが、他の権利（例: プライバシー、道徳的権利）が制限する可能性があります。
ご質問があれば @torisan_unya まで（任意）。
Torisan Unya [@torisan_unya]
### English:
Copyright © 2025 Torisan Unya [@torisan_unya]. All rights reserved.
The novel generation prompt described in this document (Title: AI-Assisted Novel Generation Prompt - CO-STAR & StoryWriter Hybrid Framework) is published under a Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0). License details: https://creativecommons.org/licenses/by-sa/4.0/.
Usage Permission: You are free to copy and redistribute the material in any medium or format (Share), and to remix, transform, and build upon the material for any purpose, even commercially (Adapt). The licensor cannot revoke these freedoms as long as you follow the license terms. However, any modified material must be distributed under the same CC BY-SA 4.0 license.
Attribution Requirement: In all uses, modifications, and distributions, you must give appropriate credit to the original author (Torisan Unya [@torisan_unya]), provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. Example: "This prompt is based on the original work by Torisan Unya [@torisan_unya]. Changes made (CC BY-SA 4.0)."
For AI/machine learning use: Attribute as above in outputs or derivatives.
Prohibited Actions: Prohibited to claim as "one's own original" or use without attribution. You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits. Reserves the right to stop misuse if discovered.
Additional Info: Created on September 8, 2025. Based on the original shared on X (formerly Twitter) (X account link: https://x.com/torisan_unya). Welcomes feedback and derivative works, but requests ethical compliance. You do not have to comply with the license for public domain elements or where your use is permitted by an exception or limitation. However, other rights such as publicity, privacy, or moral rights may limit your use.
Questions (if any): @torisan_unya (optional).
Torisan Unya [@torisan_unya]
[作成日: 2025年9月8日] / [Date: September 8, 2025]
---
If specifying variables is troublesome, please have GROK propose them as follows:
使用例　変数の指定が面倒なら、以下のようにGROKに提案させてください
---
## English Version
This is the complete English version of the prompt framework, structured identically to the Japanese version below for bilingual support. It enhances accessibility for international users (e.g., English-preferring researchers or creators). Core content unchanged; only translated for clarity and global usability. Includes enhanced "Variable Proposal Mode" and a new usage example (SF Adventure with Mars landing trouble, 5000 words). Document lists incorporate 2025 latest arXiv papers (verified via web_search: "latest arXiv AI story generation 2025", adding arXiv:2509.00481 and arXiv:2509.04481).
### AI-Assisted Novel Generation Prompt Framework: Grok Heavy Edition (Updated September 2025)
This document is an advanced prompt for long-form fiction generation using xAI's Grok. It modularizes based on arXiv papers to achieve natural psychological conflict depiction, multimodal integration, and coherence assurance. As a public demo, it's immediately applicable for creators and researchers.
### AI Proposal Mode (Newly Added/Enhanced)
Before generation, propose variables based on user input (e.g., "SF Adventure, Mars landing trouble, 5000 words"). Use web_search for the latest 2025 arXiv (query example: "latest arXiv AI story generation 2025"). Proposal content:
* theme: e.g., SF Adventure (fits user idea).
* document list: 1-2 relevant arXiv per variable (e.g., for SF tech: arXiv:2508.03137 "Long Story Generation via Knowledge Graph" for plot consistency; integrated with SEED-Story arXiv:2407.08683. 2025 latest: arXiv:2509.00481 "Multi-Agent Data Visualization and Narrative Generation" for narrative enhancement; arXiv:2509.04481 "Narrative-to-Scene Generation: An LLM-Driven Pipeline for 2D Visual Storytelling" for scene visualization).
* generation instructions: Auto-create scenes/details, internal conflicts (bias<5%, linked to multimodal triggers like dust storm visuals).
* target word count: User-specified or proposed (e.g., 5000 words). Ensure consistency (e.g., link psychological arc to tech AI and environmental fog). Output proposed variables, then generate full prompt.
### Full Novel Generation Prompt
Prompt Engineering Framework Light Integration (based on arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain, Medium 2025 practices): Context=[document list + theme], Objective=[plot fit >95%, ethics check: internal conflict bias verification], Style=[embed style sample, emphasize psychological conflicts]. Flexible adjustment with variables [theme]/[target word count].
Modularization and Adaptive Iteration (based on arXiv:2504.10179 "The Future of MLLM Prompting is Adaptive" by Arsalan Shahid / arXiv:2508.05012 "Making Prompts First-Class Citizens for Adaptive LLM Pipelines" by Alexander Lee): Divide into 2 modules (psychological control: internal conflicts/RLHF, description balance: emotion/sensory adjustment). Dynamic adjustment after SCORE (thin emotion detection → +1 loop, over 5000 words → ANN approximation option). This ensures consistent emotional propagation (tension peak → release afterglow).
theme: [specified theme, e.g., SF Adventure, Mystery Psychological Suspense, Historical Drama]
You are an AI-assisted novel writer specializing in [theme] fiction. Refer to the following documents: [document list].
[Specified scene or instruction details, e.g., Episode 1.1 specified scene S1.1_SCENE004.1]
[Additional instructions, e.g., Generate along the overall plot progression. Depict internal conflicts naturally per arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang criteria (bias<5%).]
Aim for a target word count of [target word count] and adjust (apply adaptive scaling).
StoryWriter (simulate arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia): Maximize accuracy/creativity with Forward/Backward 2 phases (integrate arXiv:2401.14423 CoT/Reflection). CPC (arXiv:2409.00102 "Collective Predictive Coding as Model of Science" by Shiro Takagi) for agent agreement on shared symbols (psychological/plot elements).
Multimodal Extension (based on arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yang): Add visual/auditory modalities to CPC (e.g., fog's damp scent/wind's whisper sound as psychological triggers). In Forward, integrate Grok tool options (view_image/view_x_video for reference, e.g., wet shadows under fog; virtual description if delayed). Enrich environmental changes with visually nuanced descriptions.
CodeMonkeys (integrate arXiv:2501.14723 "CodeMonkeys: Scaling Test-Time Compute for Software Engineering" by Bradley Brown): Draft code editing style, 3-5 iterations (virtual tests) for consistency >95%. Self-Consistency (add to Backward, arXiv:2502.06233 "Confidence Improves Self-Consistency in LLMs" by Amir Taubenfeld): Multiple draft voting for 100% accuracy.
RLHF Elements (based on arXiv:2508.18642 "RLMR: Reinforcement Learning with Mixed Rewards for Creative Writing" by Jianxing Liao / arXiv:2508.21476 "Igniting Creative Writing in Small Language Models" by Xiaolong Wei): Embed pseudo-loop in Backward (max 3 times), emotion nuance reward function (conflict easing +1, monotonous -1; naturalize internal conflict transitions, e.g., reinforce tension peak → release afterglow). Refine emotional fluctuations with Grok logic.
SCORE (arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang) for coherence verification (RLHF bias<5%).
Embed Style Sample: [style sample].
1. Confirm each episode scenario and set as basic. Apply modules: psychological control/description balance in parallel.
2. Forward Phase (Task Decomposition & Parallel Generation): Decompose tasks into 3 layers (introduction-climax-resolution) per Prompt Engineering Objective. Form agent teams per layer (roles: plot proposal, research integration, description refinement, evaluation). Query documents, strengthen psychological depiction with CPC shared symbols (e.g., natural integration of internal conflicts + visual/auditory triggers; Grok tool option input). 3-5 trajectory parallel generation (drafts + tests, ensemble voting selection: immersion >90%, consistency >95%).
3. Backward Phase (Iterative Refinement & Error Correction + Self-Consistency/SCORE/RLHF Integration): After drafts, CodeMonkeys loop 3-5 times (virtual tests: SCORE criteria e.g., "internal conflicts >90%?", consistency >95%, omissions <5%; adaptive extension possible). Pseudo RLHF loop (max 3 times): Apply before Self-Consistency, refine emotions with reward function (r>0.8 approval). Self-Consistency: 3-5 draft generation + voting (Reflection-based error correction e.g., "strengthen internal depiction"). Self-reflection: [reflection item list] applied 4 times, continue regeneration if unmet. Ethics check: Internal bias verification via Prompt Engineering.
4. Integration & Verification: Summarize continuous text from layers, confirm consistency with SCORE (no markdown; dynamic module adjustment). XAI Explanation: Key contributions (e.g., CPC improves psychological/sensory consistency by 70%, RLHF enhances emotional humanness by +15%, Self-Consistency voting solves >57%, SCORE coherence >95%). Integrate documents, plot fit >95%.
### Output Format:
Episode Title: Creatively based on theme
Narrative Text: Continuous full text (target word count adjusted)
Technical Reflection: StoryWriter/CPC/CodeMonkeys/Self-Consistency/SCORE/RLHF/Multimodal/Adaptive Summary (e.g., "Forward parallel + sensory optimization, Backward RLHF voting improves emotion 95%, module scale efficiency +20%")
XAI Explanation:
* Extended CPC Shared Symbols: Psychological/Multimodality Consistency 70% Improvement
* Self-Consistency + RLHF Voting: 100% Accuracy, Multi-Angle Emotion Nuance Verification
* SCORE Test: Inconsistencies <5%, Immersion >90%
* Adaptive Module: Scene Length Scaling for Dynamic Stability [theme]-Oriented Style: [Style details, e.g., Prioritize direct excitement expression, emphasize psychological conflicts, multi-sensory nuanced depiction (non-sensual).]
### Usage Examples
* theme: SF Adventure
* target word count: 2000 words
* document list: [List of related materials, e.g., arXiv:2506.16445 "StoryWriter" for multi-agent generation]
* generation instructions: [Specific scene specification, e.g., space exploration adventure scene]
(Newly Added: Variable Proposal Mode Example)
User Input: "SF Adventure, Mars landing trouble, 5000 words."
AI Proposal:
* theme: SF Adventure (fits user idea, emphasizes SF elements like nuclear AI and environmental trouble).
* document list: [arXiv:2506.02347 "STORYTELLER: An Enhanced Plot-Planning Framework for Coherent and Cohesive Story Generation" for plot planning and consistency; arXiv:2508.03137 "Long Story Generation via Knowledge Graph and Literary Theory" for long-form story KG construction; 2025 latest addition: arXiv:2509.00481 "Multi-Agent Data Visualization and Narrative Generation" for multi-agent narrative enhancement; arXiv:2509.04481 "Narrative-to-Scene Generation: An LLM-Driven Pipeline for 2D Visual Storytelling" for scene visualization integration].
* generation instructions: Humanity's first Mars landing ship encounters dust storm trouble; astronaut's tension routine → panic response → relieved landing, linked to 2050 nuclear AI stability. Add internal conflicts (bias<5%): Protagonist's anxiety (visual: red dust vortex, auditory: wind roar, tactile: ship vibration) contrasted with AI's logical stability. Link psychological arc with multimodal triggers to tech AI and environmental fog (dust storm).
* target word count: 5000 words (as user-specified, adjust with adaptive scaling).
Based on these proposed variables, generate the full prompt and execute the novel (e.g., Episode Title "The Crimson Storm of Mars - Trial of Landing", narrative text depicting tension → panic → relief psychological arc. Detailed output example: Continuous story around protagonist Alex's internal conflicts and nuclear AI Omega's stability, approx. 5000 words).
-------------------------
## 日本語版
### AI支援小説生成プロンプトフレームワーク：Grok Heavy版（2025年9月更新）
このドキュメントは、xAIのGrokを活用した長編フィクション生成のための先進プロンプトです。arXiv論文を基にモジュール化し、心理葛藤の自然描写、マルチモーダル統合、一貫性確保を実現。公開デモとして、クリエイターや研究者が即適用可能。
### AI提案モード（新規追加・強化）
生成前に、ユーザーの入力（例: 「SFアドベンチャー、火星着陸トラブル、5000字」）に基づき変数を提案。web_searchで2025年最新arXivを検索（クエリ例: "latest arXiv AI story generation 2025"）。提案内容:
* theme: 例: SFアドベンチャー (ユーザーアイデア適合)。
* ドキュメントリスト: 変数ごとに1-2件の関連arXiv (例: SF技術用: arXiv:2508.03137 "Long Story Generation via Knowledge Graph" でプロット一貫性; SEED-Story arXiv:2407.08683 と統合。2025最新: arXiv:2509.00481 "Multi-Agent Data Visualization and Narrative Generation" でナラティブ強化; arXiv:2509.04481 "Narrative-to-Scene Generation: An LLM-Driven Pipeline for 2D Visual Storytelling" でシーン視覚化)。
* 生成指示: シーン/詳細を自動作成、内面葛藤 (bias<5%、塵嵐視覚などのマルチモーダルトリガーと連動)。
* 目標字数: ユーザー指定 or 提案 (例: 5000字)。 整合確保 (例: 心理アークを技術AIと環境霧にリンク)。提案変数を出力後、完全プロンプト生成。
### 小説生成プロンプト（全文）
Prompt Engineering Framework軽統合 (arXiv:2401.14423 "Prompt Design and Engineering: Introduction and Advanced Methods" by Xavier Amatriain基盤, Medium 2025 practices): Context=[ドキュメントリスト+theme], Objective=[プロット適合>95%、倫理チェック: 内面葛藤バイアス検証], Style=[スタイルサンプル埋め込み, 心理葛藤強調]。変数[theme]/[目標字数]で柔軟調整。
モジュール化と適応型イテレーション (arXiv:2504.10179 "The Future of MLLM Prompting is Adaptive" by Arsalan Shahid / arXiv:2508.05012 "Making Prompts First-Class Citizens for Adaptive LLM Pipelines" by Alexander Lee基盤): 全体を2モジュール（心理制御: 内面葛藤/RLHF、描写バランス: 感情/感覚調整）に分割。SCORE後動的調整（感情薄検知→ループ+1回、5000字超→ANN近似オプション）。これで感情波及一貫（緊張頂点→解放余韻）。
theme: [指定テーマ, 例: SFアドベンチャー, ミステリー心理サスペンス, 歴史ドラマ]
あなたは、[theme]をテーマにしたフィクションを専門とするAI支援小説ライターです。以下のドキュメントを参照：[ドキュメントリスト]。
[指定シーンや指示の詳細、例: 1.1話の指定シーン S1.1_SCENE004.1]
[追加の指示、例: 全体のプロット進行に沿って生成。内面葛藤の描写はarXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang基準で自然表現（bias<5%）。]
生成する文章の目標字数は[目標字数]を目指し、調整せよ（適応スケール適用）。
StoryWriter (arXiv:2506.16445 "StoryWriter: A Multi-Agent Framework for Long Story Generation" by Haotian Xia) をシミュレート: Forward/Backward 2フェーズで正確性/創造性最大化 (arXiv:2401.14423 CoT/Reflection統合)。CPC (arXiv:2409.00102 "Collective Predictive Coding as Model of Science" by Shiro Takagi) で共有シンボル（心理/プロット要素）をエージェント間合意。
マルチモーダル拡張 (arXiv:2407.08683 "SEED-Story: Multimodal Long Story Generation with Large Language Model" by Shuai Yang基盤): CPCに視覚/音響モダリティ追加（e.g., 霧の湿気香り/風のささやき音を心理トリガー）。ForwardでGrokツールオプション連携（view_image/view_x_videoで参照, e.g., 霧下の影濡れ; 遅延時仮想記述）。環境変化を視覚婉曲豊かに。
CodeMonkeys (arXiv:2501.14723 "CodeMonkeys: Scaling Test-Time Compute for Software Engineering" by Bradley Brown) 統合: ドラフトコード編集風、3-5回イテレーション（仮想テスト）で一貫性>95%。Self-Consistency (arXiv:2502.06233 "Confidence Improves Self-Consistency in LLMs" by Amir Taubenfeld) をBackward追加: 複数ドラフト投票で正確性100%。
RLHF要素 (arXiv:2508.18642 "RLMR: Reinforcement Learning with Mixed Rewards for Creative Writing" by Jianxing Liao / arXiv:2508.21476 "Igniting Creative Writing in Small Language Models" by Xiaolong Wei基盤): Backwardに擬似ループ（3回上限）組み込み、感情ニュアンス報酬関数（葛藤弱まり+1、単調-1; 内面葛藤移行自然化, e.g., 緊張頂点→解放余韻強化）。Grok論理で感情揺らぎ洗練。
SCORE (arXiv:2503.23512 "SCORE: Story Coherence and Retrieval Enhancement for AI Narratives" by Jianhui Wang) でcoherence検証（RLHF bias<5%）。
スタイルサンプルを埋め込み: [スタイルサンプル]。
1. 各話シナリオを確認し、基本設定とする。モジュール適用: 心理制御/描写バランスで並列。
2. Forward Phase (タスク分解 & 並列生成): Prompt Engineering Objectiveでタスクを3レイヤー（導入・クライマックス・結末）に分解。各レイヤーでエージェントチーム編成（役割: プロット提案、研究整合、描写洗練、評価）。ドキュメントクエリし、心理描写をCPC共有シンボルで強化（e.g., 内面葛藤+視覚/音響トリガー自然統合; Grokツールオプションインプット）。3-5軌跡並列生成（ドラフト+テスト、ensemble voting選択: 没入感>90%、一貫性>95%）。
3. Backward Phase (イテレーティブ精錬 & 誤差修正 + Self-Consistency/SCORE/RLHF統合): ドラフト後、CodeMonkeysループ3-5回（仮想テスト: SCORE基準 e.g., "内面葛藤>90%か"、一貫性>95%、省略<5%; 適応延長可能）。擬似RLHFループ（3回上限）: Self-Consistency前適用、報酬関数で感情洗練（r>0.8 r > 0.8 r>0.8承認）。 Self-Consistency: 3-5ドラフト生成+投票（Reflectionベース誤差修正 e.g., "内面描写強化"）。自己反省: [反省項目リスト] 4回適用、再生成未達時継続。倫理チェック: Prompt Engineeringで内面バイアス検証。
4. 統合 & 検証: レイヤー連続テキストまとめ、一貫性SCORE確認（markdown禁止; モジュール動的調整）。XAI説明: 主要決定寄与（e.g., CPCで心理/感覚一貫性70%向上、RLHFで感情人間らしさ+15%、Self-Consistency投票で解決率>57%、SCOREでcoherence>95%）。ドキュメント統合、プロット適合>95%。
### 出力形式:
エピソードタイトル：テーマに基づいて創作
叙述テキスト：連続した全文（目標字数調整）
技術反省：StoryWriter/CPC/CodeMonkeys/Self-Consistency/SCORE/RLHF/マルチモーダル/適応要約（e.g., "Forward並列+感覚最適化、Backward RLHF投票で感情95%向上、モジュールスケールで効率+20%"）
XAI説明：
* 拡張CPC共有シンボル: 心理/マルチモダリティ一貫性70%向上
* Self-Consistency+RLHF投票: 正確性100%、感情ニュアンス多角検証
* SCOREテスト: 不整合<5%、没入感>90%
* 適応モジュール: シーン長スケールでダイナミズム安定 [theme]向けスタイル：[スタイル詳細、例: 興奮直接表現優先、心理葛藤強調、多感覚婉曲描写（非官能的）。]
### 使用例
* theme: SFアドベンチャー
* 目標字数: 2000字
* ドキュメントリスト: [関連資料のリスト、例: arXiv:2506.16445 "StoryWriter" でマルチエージェント生成]
* 生成指示: [具体的なシーン指定、例: 宇宙探査の冒険シーン]
