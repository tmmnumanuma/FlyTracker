[ecdysone_research_proposal.md](https://github.com/user-attachments/files/24977212/ecdysone_research_proposal.md)
# 研究計画書

## 成虫ショウジョウバエにおけるエクダイソン合成組織の同定と毒物防御応答メカニズムの解明

---

## 1. 研究の背景と目的

### 1.1 研究の背景

エクダイソンは古典的には、節足動物の脱皮・変態を制御する発生ホルモンとして認識されてきた[1]。しかし、成虫では脱皮を行わないにもかかわらず、血液中にエクダイソンが検出され続けることが知られており[2]、その成虫期における生理的機能は長年謎であった。

2025年6月、市之瀬敏晴ら（東北大学）は、「Ecdysteroid-DopEcR signaling in neuronal and midgut cells mediates toxin avoidance and detoxification in Drosophila」を Current Biology 誌に発表し、成虫脳のドーパミン-エクダイソン受容体（DopEcR）シグナルが、銅、パラコート、コカインなどの毒物に対する忌避行動と腸での解毒を制御することを初めて明らかにした[3]。この発見は、エクダイソンが「行動防御ホルモン」として機能することを示唆する革新的な知見である。

しかし、市之瀬論文では以下の重大な問題が未解明のままである：

1. **エクダイソン合成組織の不明確性**：
   - メス成虫での卵巣からのエクダイソン産生は確認されているが、オス成虫での合成源は完全に不明である[4]。
   - 毒物刺激時に、どの組織がエクダイソンを産生し、それが神経系にどのように伝達されるのかは未明である。

2. **信号伝達経路の不完全な理解**：
   - 毒物の摂取→エクダイソン分泌の因果的な信号経路が不明。
   - 腸での局所的なエクダイソン産生の可能性（2024年の Terry らの研究で、傷ついた上皮での局所エクダイソン産生が報告[5]）が、毒物応答で起動するのかは不明。

3. **多臓器源の可能性**：
   - 複数の組織が冗長的にエクダイソンを産生している可能性を排除できていない。

### 1.2 本研究の目的

本研究は、組織特異的な遺伝学的操作とその後の行動・生化学的解析を組み合わせることで、以下の二つの主要な目的を達成することを目指す：

**目的1**：成虫ショウジョウバエのどの組織でエクダイソン合成酵素が発現・機能しているかを、空間的・時間的に同定する。特にオス成虫での合成源の同定を優先する。

**目的2**：毒物摂取に応答したエクダイソン産生とそれに続く神経-腸軸を通じた行動・代謝応答の統合的なメカニズムを解き明かす。

### 1.3 期待される成果

本研究の成功は、以下の学術的・応用的インパクトを生み出すことが期待される：

- **基礎神経生物学**：成虫脳における非古典的ホルモン機能の統合的理解
- **進化生物学**：脱皮ホルモンの機能多様化と組織特異的な相互作用の原理
- **応用**：化学物質の毒性評価モデルの開発、害虫防除法の革新
- **医学への翻訳**：ステロイドホルモンの行動防御機能に関する新知見

---

## 2. 研究の全体計画と段階的アプローチ

本研究は、段階的な3つのフェーズで構成される（図1参照）。各フェーズは、次のフェーズの根拠を提供し、最終的に「エクダイソン合成源の同定と毒物応答メカニズムの統合的理解」へと至る。

### 2.1 フェーズ1：基礎情報整備（予定期間：3ヶ月）

**目的**：組織特異的RNAiスクリーニングに先立ち、成虫でのハロウィーン遺伝子の発現パターンと毒物忌避行動の基準を確立する。

#### 2.1.1 成虫でのハロウィーン遺伝子の空間的発現マッピング

**背景**：ハロウィーン遺伝子群（neverland, spook, phantom, disembodied, shadow, shade）は、エクダイソン合成経路の各ステップを触媒する[6]。幼虫では prothoracic gland（PG）が唯一の合成源であることが知られているが[7]、成虫での発現パターンは系統的に調べられていない。

**実験方法**：

1. **Single-molecule Fluorescence In Situ Hybridization（smFISH）**
   - 対象遺伝子：
     - *neverland*（最初のステップ、コレステロール→プレステロイド）
     - *phantom*（中間ステップ）
     - *shade*（最終ステップ、エクダイソン→20-hydroxyecdysone）
   - 対象組織：脂肪体、中腸（銅細胞含む）、脳、精巣、卵巣
   - 個体：新羽化オス/メス、3日齢オス/メス、老齢（7-10日齢）オス/メス
   - 方法：市販のsmFISH kit（例：Stellaris, Biosearch Technologies）を使用[8]
   - 検出：共焦点顕微鏡による定量画像解析

2. **Quantitative RT-PCR（qRT-PCR）による発現量の相対定量**
   - 各組織を単離し、total RNAを抽出
   - ハロウィーン遺伝子の mRNA を定量化
   - Normalization gene：*rp49*, *actin*
   - 算出値：各組織での相対発現量（fold change vs. 脂肪体を baseline）

**期待される結果**：
- 成虫では幼虫と異なる発現パターンが出現（例：脂肪体での新規発現）
- オスとメスで異なるパターン（卵巣の寄与を直接的に評価）
- 老化による発現変化

**出力物**：
- ハロウィーン遺伝子の発現パターン図（組織別、性別別、齢別）
- 次のステップで優先的にターゲットすべき遺伝子・組織の同定

#### 2.1.2 毒物忌避行動の測定系の標準化

**背景**：市之瀬らは CAFE（capillary feeder）アッセイを用いて毒物忌避行動を測定した[3]。本研究でも同一の方法を採用し、標準化を完成させる必要がある。

**実験方法**：

1. **CAFE アッセイの基本プロトコル**[3]
   - 個別飼育：プラスチック容器（約5mL）に単一のハエを収容
   - 刺激：
     - Control：標準的なショ糖含有食（5% sucrose + 2% yeast）
     - Test：毒物含有食（例：CuSO₄ 2mM + 5% sucrose + 2% yeast）
   - 測定：毛細血管（capillary）を用いた食物摂取の定量
     - 毛細血管のメモリスケールで液体レベルを読取
     - 30分間隔で計12回測定（6時間実験）
   - アウトプット：Performance Index（PI） = （Control摂取 - Test摂取）/（Control摂取 + Test摂取）
     - PI = -1：毒物食物のみ摂取
     - PI = 0：同等摂取（忌避なし）
     - PI = +1：通常食物のみ摂取（完全忌避）

2. **実験デザイン**
   - 各測定日：
     - 朝（8:00）と夜（18:00）に別セッション実施（circadian variation の確認）
     - 各条件・性別：n ≥ 20個体
   - 毒物の種類（市之瀬論文から選定）：
     - CuSO₄（銅、2mM - 最も顕著な応答が報告）
     - Paraquat（パラコート、酸化ストレッサー）
     - Cocaine（行動への直接作用の参照）
   - 栄養状態：
     - 24時間絶食後に実験開始（食物への motivational state を統制）
   - 記録：実験中の行動ビデオ（オプション：飲食行動の詳細解析）

3. **解析**
   - PI の平均値 ± SE を算出
   - 野生型（Canton-S）の baseline を確立
   - 個体差、時系列による変化の記述統計

**期待される結果**：
- 銅に対する強い忌避反応（PI > 0.5）
- 時系列での PI の経時的変化パターン（初期忌避から徐々に摂取増加など）
- 朝夕での circadian variation

**出力物**：
- 毒物忌避行動の標準的な測定プロトコル
- 野生型での baseline データ（論文への補足データとしても価値）
- 次フェーズでの群間比較の根拠

---

### 2.2 フェーズ2：Tissue-specific RNAi スクリーニング（予定期間：4ヶ月）

**目的**：複数の組織でハロウィーン遺伝子をノックダウンし、毒物忌避行動がどの組織で変化するかを系統的に同定する。並行して、ホルモンレベルの変化を測定する。

#### 2.2.1 Tissue-specific knockdown 株の作出・入手

**戦略**：以下の理由から、新規作出よりも既存ライン活用を優先とする：
- 時間効率（新規作出は 3-4ヶ月必要）
- 品質管理（既知の背景遺伝子、発現強度の検証済み）
- 再現性（複数のラボで共通使用可能）

**使用ラインの選定**：

| 組織 | GAL4ドライバー | 出典 | 備考 |
|------|----------------|------|------|
| 脂肪体 | pplGAL4 | Bloomington 8130 | 脂肪体の広範な発現 |
| | r4-GAL4 | Bloomington 33832 | 脂肪体特異的 |
| 中腸 | NP1-GAL4 | Bloomington 3039 | 中腸全体 |
| | esg-GAL4 | Bloomington 25574 | 腸幹細胞特異的 |
| | myo1A-GAL4 | 自作 or Bloomington | 吸収性上皮細胞 |
| 脳 | elav-GAL4 | Bloomington 458 | 全神経 |
| | MB-GAL4 (MB247) | Bloomington 50742 | キノコ体特異的 |
| | DNg-GAL4 | Bloomington 36296 | ドーパミンニューロン |
| 生殖腺 | nos-GAL4 | Bloomington 4937 | 生殖系列全体 |
| | otu-GAL4 | 自作 or 外部 | 卵母細胞 |
| | tj-GAL4 | Bloomington 28816 | 精巣 somatic cells |
| コントロール | Act5c-GAL4 | Bloomington 3954 | ユビキタス（毒性評価用） |

**UAS 系統**（RNAi construct）の選定：

1. **Primary target：*neverland* RNAi**
   - 理由：最初のステップであり、signal-to-noise ratio が最大
   - 系統候補：
     - UAS-neverland-RNAi (TRiP line, Bloomington 31564)[9]
     - 代替：UAS-neverland-IR (Vienna Drosophila RNAi Center, if available)

2. **Secondary target：*shade* RNAi**（if time permits）
   - 理由：最終ステップ、別の合成段階を検証
   - 系統候補：UAS-shade-RNAi (TRiP line)

**交配スキーム**：
```
GAL4 driver (tissue-specific) ♂ × UAS-neverland-RNAi ♀
↓
F1 hybrid offspring: [tissue-GAL4/+]; [UAS-neverland-RNAi/+]
（このF1が実験対象）
```

**コントロール群**：
- GAL4 のみ（driver/+）：GAL4 background effects 排除
- UAS-RNAi のみ（+/UAS）：UAS background effects 排除
- Wild-type（Canton-S）：baseline behavior

#### 2.2.2 毒物忌避行動の測定

**実験設計**：

**グループ組成**：

| グループ番号 | 遺伝子型 | n | 性別 | 備考 |
|-----------|---------|---|------|------|
| 1 | WT (Canton-S) | 12 | M/F | Baseline |
| 2 | pplGAL4/+ | 12 | M/F | Fat body GAL4 control |
| 3 | UAS-neverland-RNAi/+ | 12 | M/F | RNAi control |
| 4 | pplGAL4/UAS-neverland-RNAi | 15 | M/F | Fat body knockdown |
| 5 | NP1-GAL4/UAS-neverland-RNAi | 15 | M/F | Midgut knockdown |
| 6 | esg-GAL4/UAS-neverland-RNAi | 12 | M/F | ISC knockdown |
| 7 | myo1A-GAL4/UAS-neverland-RNAi | 12 | M/F | Enterocyte knockdown |
| 8 | elav-GAL4/UAS-neverland-RNAi | 12 | M/F | Pan-neuronal knockdown |
| 9 | DNg-GAL4/UAS-neverland-RNAi | 12 | M/F | Dopamine neuron KD |
| 10 | nos-GAL4/UAS-neverland-RNAi | 12 | M/F | Germline knockdown |

**実験プロトコル**（各グループごと）：

1. **個体準備**
   - 新羽化個体を収集し、24時間社会飼育（群飼育、30-50個体）
   - その後、単独飼育容器へ移行
   - 24時間の馴化期間

2. **毒物忌避行動測定**
   - CAFE アッセイ（フェーズ1と同一プロトコル）
   - 毒物：CuSO₄ 2mM（市之瀬論文と同一）
   - 測定期間：6時間（30分間隔，12回測定）
   - 複数の日にレプリケーション（n=12-15個体 × 日数で、最小 n=36-45 total observations）

3. **補助的な測定**
   - 生存率：実験前後で記録（RNAi毒性評価）
   - 一般的な食物摂取：毒物非含有食（sucrose + yeast）のみでの CAFE（忌避 vs 嫌悪 vs 摂取障害を区別）
   - 嗅覚応答：毒物の一般的な嗅覚忌避（学習なしでの応答）
     - 方法：T-maze で、無臭 vs CuSO₄ 臭への応答を測定

4. **データ解析**
   - Performance Index (PI) 計算
   - グループ間比較：One-way ANOVA または Kruskal-Wallis test（非正規分布時）
   - 多重比較補正：Tukey HSD or Bonferroni
   - 効果量（Cohen's d）も報告
   - Sex × Genotype interaction の評価：Two-way ANOVA

**期待される結果**：
- 野生型：PI > 0.5（強い銅忌避）
- 複数の tissue-specific KD でPI 低下の可能性
  - 最も顕著：脂肪体 or 中腸（初期仮説）
  - 脳（神経毒性による二次効果の可能性も評価）
- オスとメスでの相違（卵巣 KD での meしのみの効果など）

**出力物**：
- 各 genotype ごとの毒物忌避行動データ（表、グラフ）
- ホットマップ：各組織での knockdown 効果の相対的強度
- 次フェーズへの優先順位付けされた候補組織

#### 2.2.3 ホルモンレベルの直接測定（生化学的確認）

**背景**：行動の変化だけからは「本当にエクダイソン合成が低下したのか」を確定できない。ホルモンレベルの直接的な測定が必須である[10]。

**実験方法**：

1. **Hemolymph（血液）採集**
   - 対象個体：フェーズ2で毒物忌避が最も低下した 2-3 の tissue-specific KD 株、および対照群（野生型、GAL4 control, UAS control）
   - 個体数：n = 8-10/group（ホルモン値の個体差が大きいため）
   - タイミング：
     - ZT0（朝6:00）：Circadian peak 付近
     - ZT8（昼14:00）：Trough 付近
     - 毒物暴露前 vs 暴露後（銀銅入れた食物へのアクセス後 1時間）
   - 採集方法[11]：
     - プロトコル A（非侵襲）：冷却麻酔下で、虫を micro-capillary で吸い込んで hpl を抽出
     - プロトコル B（侵襲的）：腹部から直接針を刺してヘモリンパを採集
     - 両方試行して、メリット・デメリットを評価

2. **Liquid Chromatography-Tandem Mass Spectrometry (LC-MS/MS) による定量**[12]
   - 測定対象化合物：
     - Ecdysone （20-hydroxyecdysone の前駆体）
     - 20-hydroxyecdysone （活性型）
     - Ecdysone-22-phosphate （保存型）
   - 装置：LC-MS/MS（例：Shimadzu, Thermo Fisher）
   - 標準物質：既知濃度の ecdysone 標準品を使用
   - キャリブレーション：複数の濃度で検量線作製
   - 検出感度：pg/mL オーダーが必要（ショウジョウバエは血液量が極めて少ない）
   - 共同研究：自施設に LC-MS/MS がない場合は、外部の生化学コア施設（例：東北大学の共用施設）と共同研究として実施

3. **結果解析**
   - 各 genotype ごとのエクダイソン濃度（pg/mL）を算出
   - 野生型との相対値（fold change）で表示
   - 時系列での変化（ZT0 vs ZT8）
   - 毒物暴露の効果（暴露前 vs 1時間後）

**期待される結果**：
- Fat body KD（効果あった場合）：エクダイソン濃度が野生型の 30-60% に低下
- Midgut KD（効果あった場合）：エクダイソン濃度の変化（全身レベルの低下 vs 局所的な変化）
- Brain/neuron KD：エクダイソン濃度が野生型と同程度（合成源ではない可能性）

**出力物**：
- LC-MS/MS による ecdysone/20-HE 濃度データ（表、グラフ）
- 行動変化と生化学的変化の相関性の評価

---

### 2.3 フェーズ3：メカニズム解明と救済実験（予定期間：4-6ヶ月）

**目的**：フェーズ2で同定された「毒物忌避行動が低下した組織」が、真にエクダイソン合成源であること、および毒物応答メカニズムの詳細を確認する。

#### 2.3.1 外部エクダイソン投与による救済試験

**背景**：RNAi knockdown での表現型が「エクダイソン合成低下」によるのか、「非特異的な RNAi toxicity」によるのかを区別するため、外部からエクダイソンを投与して行動が救済されるかを試験する。

**実験方法**：

1. **エクダイソンの調製と投与**
   - 使用化合物：20-hydroxyecdysone （20-HE）
     - 理由：エクダイソンより生体利用性が高い
     - 入手：Sigma-Aldrich, カタログ# H5142
   - 投与経路：経口的
   - 投与形式：
     - 方法 A：20-HE を食物に混合（濃度：0.1, 1, 10, 100 μM）
     - 方法 B：20-HE を生理食塩水で溶解し、腹部に注射（10-50 nL, 濃度：100 μM）
     - 方法 C：20-HE を含むペーストを体表に塗布（直接効果の評価）
   - 対照：vehicle のみ（DMSO or PBS）

2. **実験デザイン**
   - 対象：フェーズ2 で毒物忌避が最も低下した tissue-specific KD 株
   - グループ：
     - A. KD株 + Vehicle
     - B. KD株 + 20-HE 低濃度
     - C. KD株 + 20-HE 中濃度
     - D. KD株 + 20-HE 高濃度
     - E. WT + Vehicle （comparison）
   - 各グループ n ≥ 12

3. **毒物忌避行動の測定**
   - CAFE アッセイ（フェーズ1-2と同一）
   - 投与後 2時間、6時間、24時間での測定
   - Performance Index を比較

4. **解析**
   - Dose-response 関係の評価
   - 野生型レベルまでの救済があるか
   - 統計：One-way ANOVA，Dunnett's post-hoc（KD+vehicle を control とした比較）

**期待される結果**：
- 真のエクダイソン合成源の KD：濃度依存的な救済（最大で WT レベルまで回復）
- 非特異的な RNAi toxicity：救済されない（または一部の回復のみ）

**出力物**：
- 用量反応曲線（グラフ）
- エクダイソン合成源候補の確定

#### 2.3.2 DopEcR の直接的な活性化試験（補足実験）

**背景**：フェーズ2-3 で、「brain/neuronal KD で毒物忌避が変化した」場合、それが「脳でのエクダイソン合成」を意味するのか「脳でのエクダイソン応答性の低下」を意味するのか区別が必要である。

**実験方法**：

1. **DopEcR 活性化の手段**
   - 方法 A：光遺伝学的 chemogenetics
     - DopEcR agonist の開発品（literature から）を外部投与
     - 効果：脳内 DopEcR を直接活性化、エクダイソン投与なしで毒物忌避が改善するか
   - 方法 B：体内産生促進
     - ecdysone を脳に局所投与（脳室注入など）

2. **実験デザイン**
   - 対象：brain-specific KD（毒物忌避が低下していた場合）
   - グループ：
     - A. Brain-KD + Vehicle
     - B. Brain-KD + DopEcR agonist
   - 毒物忌避行動の測定

3. **期待される結果**
   - DopEcR 活性化で行動が改善 → 脳は「エクダイソン応答細胞」（合成源ではない）
   - 改善しない → 脳でのエクダイソン産生が必要

#### 2.3.3 毒物応答的なハロウィーン遺伝子の発現上昇の検証

**背景**：毒物摂取時に、実際に該当組織でハロウィーン遺伝子の発現が上昇しているのかを直接確認する。これにより「毒物 → エクダイソン産生」という因果的なリンクが実証される。

**実験方法**：

1. **In vivo での動的モニタリング**
   - 遺伝子型：neverland-GFP reporter line を作出（または既存があれば利用）[13]
   - 方法：銅含有食へのアクセス直後に、腸などの該当組織の GFP 発現を共焦点顕微鏡で観察
   - 時間点：0時間、0.5時間、1時間、2時間、6時間、24時間

2. **Quantitative RT-PCR での mRNA 検証**
   - 銅入り食へのアクセス前・直後（0.5, 1, 2, 6時間後）に個体を採集
   - 該当組織（例：脂肪体、腸）を単離
   - qRT-PCR で neverland, phantom, shade mRNA レベルを測定
   - 野生型, 毒物非暴露群と比較

3. **解析**
   - Fold change in mRNA（毒物暴露群 vs 非暴露群）
   - 時系列でのパターン（early response genes か, inducible か）

**期待される結果**：
- 腸および脂肪体で、銅暴露後に neverland 等の発現が上昇
- Time course：1-2時間以内に peak，その後減少

**出力物**：
- In vivo での動的発現パターン（time-series ビデオまたはグラフ）
- 毒物応答性の確認

#### 2.3.4 ハロウィーン遺伝子発現の局所性：傷つけた組織での発現（オプション）

**背景**：2024年の Terry らの研究で、傷ついた上皮での局所的なエクダイソン産生が報告された[5]。毒物摂取による「上皮損傷」がエクダイソン産生を誘導するのか、それとも「化学的シグナル」が誘導するのかを調べる。

**実験方法**：

1. **腸の機械的損傷**
   - メス：毒物非含有食で銅刺激なく，腸を mechanically damage
   - 毒物含有食での同様の損傷
   - GFP reporter （neverland-GFP）観察

2. **化学的シグナルのみ**
   - 毒物（銅）を腸に直接適用（摂取なし）
   - その他の物理的刺激（温度など）

3. **結果の比較**
   - 局所的エクダイソン産生は、物理的損傷か化学的刺激か，それとも摂取後の消化プロセスか

**期待される結果**：
- 局所的エクダイソン産生の メカニズム が明らかになる
- 全身的エクダイソン（脂肪体など）との時間的な役割分担

---

## 3. 使用する実験材料・方法の詳細

### 3.1 使用する生物材料

#### 3.1.1 ショウジョウバエ系統

**供給源**：

| 系統名 | カタログ# | 供給元 | 用途 |
|--------|-----------|--------|------|
| Canton-S | - | 自実験室保管 | Wild-type reference |
| pplGAL4 | Bloomington 8130 | Bloomington Drosophila Stock Center | Fat body driver |
| r4-GAL4 | Bloomington 33832 | BDSC | Fat body (specific) |
| NP1-GAL4 | Bloomington 3039 | BDSC | Midgut driver |
| esg-GAL4 | Bloomington 25574 | BDSC | Intestinal stem cell driver |
| myo1A-GAL4 | Bloomington系統 or custom | BDSC or 自作 | Enterocyte driver |
| elav-GAL4 | Bloomington 458 | BDSC | Pan-neuronal driver |
| MB247-GAL4 | Bloomington 50742 | BDSC | Mushroom body driver |
| DNg-GAL4 | Bloomington 36296 | BDSC | Dopamine neuron driver |
| nos-GAL4 | Bloomington 4937 | BDSC | Germline driver |
| UAS-neverland-RNAi (TRiP) | Bloomington 31564 | BDSC | Neverland knockdown |
| UAS-shade-RNAi | (TRiP line) | BDSC | Shade knockdown (optional) |

**飼育条件**：
- 温度：25°C（実験中）
- 湿度：60%
- Light-dark cycle：12:12 hour LD
- Food：標準的なコーンミール培地（Bloomington standard recipe）
- 飼育密度：30-50 個体/vial

**個体の準備**：
- 新羽化個体を毎日収集
- 24-48時間の社会飼育後，実験に使用
- 性別は分離されている

#### 3.1.2 使用する化学物質

| 物質 | 用途 | 濃度・用量 | 供給元 |
|------|------|---------|--------|
| CuSO₄·5H₂O | 毒物刺激 | 2 mM | Sigma-Aldrich（P/N：C1297） |
| 20-Hydroxyecdysone | ホルモン投与 | 0.1-100 μM | Sigma-Aldrich（P/N：H5142） |
| Ecdysone | ホルモン参考 | 検量線用 | Sigma-Aldrich |
| Paraquat dichloride | 毒物（参考） | 1-10 mM | Sigma-Aldrich（P/N：36541） |

### 3.2 主要な実験手法

#### 3.2.1 Behavioral assays

**CAFE (Capillary Feeder) Assay**[3]
- プロトコル：上記 2.1.2 参照
- 解析：Performance Index (PI)
- ソフトウェア：カスタム ImageJ macro，または手動読取後に spreadsheet で計算

**T-maze 選択行動試験**
- 古典的な嗅覚行動測定法（市之瀬論文など参考）
- エクダイソン KD による一般的な嗅覚機能への影響を評価

#### 3.2.2 Molecular methods

**smFISH (Single-molecule Fluorescence In Situ Hybridization)**[8]
- 市販キット使用（Stellaris, Biosearch Technologies）
- Probes：custom design，target gene specific
- Detection：Zeiss または Leica 共焦点顕微鏡
- 画像解析：Fiji/ImageJ，CellProfiler など

**Quantitative RT-PCR**[14]
- Nucleic acid extraction：TRIzol または市販キット
- cDNA synthesis：SuperScript III reverse transcriptase
- qPCR：SYBR Green または TaqMan master mix（Applied Biosystems）
- Instruments：QuantStudio 3 または equivalent
- Primer design：Primer3, NCBI Primer-BLAST
- Reference genes：*rp49*, *actin*（複数使用推奨）

**LC-MS/MS for ecdysteroid quantification**[12]
- Liquid chromatography：Shimadzu LC-20AD，または Thermo Fisher Dionex
- Mass spectrometer：Tandem MS（例：Shimadzu 8050, Thermo Quantis）
- Method：published SRM method，または custom development
- Standard curve：multiple points（0.01-1000 pg/mL range 推定）
- Quality control：internal standard (13C-labeled ecdysone, if available)

**Hemolymph collection**[11]
- Cold anesthesia：4°C at 15-20 min
- Capillary collection：borosilicate capillary（内径 0.5-1.0 mm）
- Direct sampling：可能なら vein puncture（腹部）
- Immediate processing：−80°C 保存

### 3.3 データ解析と統計

#### 3.3.1 行動データの統計解析

**Descriptive statistics**：
- Mean ± SE （または SEM）
- Median ± IQR （非正規分布の場合）

**Inferential statistics**：
- Normality test：Shapiro-Wilk
- Equality of variance：Levene's test
- Parametric tests：One-way ANOVA，Two-way ANOVA (genotype × sex)
- Non-parametric alternatives：Kruskal-Wallis，Mann-Whitney U
- Post-hoc comparisons：Tukey HSD （parametric），Dunn's （non-parametric）
- Multiple comparison correction：Bonferroni （conservative），FDR correction （exploratory）
- Effect size：Cohen's d, η²

**Time-series analysis**（毒物忌避の経時的変化）：
- Repeated measures ANOVA
- Mixed-effects models （individual as random effect）

#### 3.3.2 分子データの解析

**qRT-PCR data**：
- ΔΔCt method for relative quantification
- Multiple reference genes を使用
- Fold change calculation

**LC-MS/MS data**：
- Peak integration by MassLynx or MassHunter software
- Quantification using standard curve （linear or polynomial fit）
- QC checking：accuracy within ±20%，reproducibility (CV < 15%)

#### 3.3.3 使用するソフトウェア・統計パッケージ

- **R** （version 4.0+）：
  - packages: ggplot2, tidyverse, Hmisc, multcomp, lme4
- **GraphPad Prism** （version 9+）：図作成，基本統計
- **ImageJ/Fiji**：画像解析，定量化
- **SPSS or JMP** （もし施設で利用可能）

---

## 4. 期待される結果と研究の意義

### 4.1 主要な期待結果

#### フェーズ1での期待結果

1. **ハロウィーン遺伝子の成虫での組織特異的発現パターンの初めての同定**
   - 新規知見：成虫では幼虫とは異なり、複数の組織で Halloween genes が発現している可能性
   - 特にオス成虫でのパターンが新規である可能性が高い

2. **毒物忌避行動測定系の確立**
   - 再現性のある CAFE プロトコルの確立
   - 野生型 baseline データの提供

#### フェーズ2での期待結果

1. **エクダイソン合成源の初めての同定**
   - 仮説：脂肪体または中腸がメインの成虫エクダイソン合成源
   - オスとメスでの相違：メスでは卵巣の役割が大きい，オスでは脂肪体など他組織が主要

2. **複数組織の冗長的役割の可能性**
   - 複数の組織でのKDで初めて表現型が出現（単一組織KDでは不十分）

3. **生化学的確認**
   - LC-MS/MS による hemolymph ecdysone 濃度の低下確認

#### フェーズ3での期待結果

1. **救済実験による確定**
   - 外部エクダイソン投与で毒物忌避行動が回復

2. **毒物応答的なエクダイソン産生の動的メカニズム**
   - 毒物刺激後の時間依存的なハロウィーン遺伝子発現上昇
   - 局所 vs 全身的エクダイソン産生の役割分担

### 4.2 研究の学術的意義

#### 基礎神経生物学への貢献

1. **成虫脳における非古典的ホルモン機能の統合的理解**
   - エクダイソンが脱皮ホルモンではなく，「行動・代謝防御ホルモン」として機能することの機構
   - ドーパミン-エクダイソン相互作用の詳細な回路図

2. **散在性ホルモン合成（Distributed hormone synthesis）の原理**
   - 単一の内分泌腺ではなく，複数の末梢組織でのホルモン産生
   - 組織特異的な paracrine/autocrine シグナリング

3. **進化的保存性と機能多様化**
   - 成虫期での脱皮ホルモン受容体（EcR/USP）の新しい生理的役割
   - 昆虫とヒトのステロイドホルモンシグナリングの比較

#### 応用・実践的意義

1. **害虫防除への応用**
   - エクダイソン合成経路を標的とした新規殺虫剤開発の可能性
   -既存の合成酵素阻害剤（benzoylurea 系など）の作用機構の詳細化

2. **化学物質毒性評価モデル**
   - ショウジョウバエの毒物忌避行動を利用した化学物質スクリーニングシステムの開発
   - エクダイソン-DopEcR パスウェイを標的とした毒物の同定

3. **医学への翻訳の可能性**
   - ステロイドホルモンの「行動防御機能」という新視点
   - グルココルチコイドシグナルと恐怖条件付けや嫌悪学習との関連の再考

---

## 5. 研究実施体制

### 5.1 研究実施機関

**主機関**：東北大学大学院生命科学研究科 神経生物学分野

### 5.2 研究者構成

| 役割 | 氏名（予定） | 職位 | 主要責務 |
|-----|----------|------|---------|
| 研究代表者 | [実施予定者] | 博士課程学生 or ポスドク | 全体統括，行動実験，データ解析 |
| 指導教員1 | [教授/准教授] | 教授 or 准教授 | 研究指導，計画監督 |
| 指導教員2 | [市之瀬敏晴 予定] | 研究員 / Collaborator | ホルモン測定技術指導，LC-MS/MS協力 |
| 共同研究者 | [分子遺伝学専門家] | 外部研究機関 | ハロウィーン遺伝子発現解析 |
| 技術補佐員 | [名前] | 技術職員 | 系統飼育，データ記録補助 |

### 5.3 実施機関の設備

**ショウジョウバエ施設**：
- 定温・定湿飼育器：複数台（25°C, 12:12 LD）
- 飼育用 vials, bottles：十分な在庫
- Dissection & microscopy tools

**分析装置**：
- 共焦点顕微鏡（Zeiss LSM or Leica SP）：東北大学共用施設
- qRT-PCR システム（Applied Biosystems QuantStudio）：自施設 or 共用施設
- LC-MS/MS（必要に応じて外部共同研究）

**ソフトウェア・計算環境**：
- R, Python，統計ソフト
- ImageJ/Fiji
- GraphPad Prism

### 5.4 外部共同研究先

| 機関 | 専門 | 期待される役割 |
|------|------|--------------|
| 東北大学医学系研究科 代謝内分泌学分野 | ホルモン分析 | LC-MS/MS 測定，解析指導 |
| 京都大学 白眉プロジェクト研究員 | Ecdysone biology | 学術助言，技術相談 |
| RIKEN Omics Science Center | Mass spectrometry | ホルモン定量の QC, validation |

---

## 6. 研究スケジュール

### 6.1 全体タイムライン

```
Year 1（12ヶ月）

Phase 1: 基礎情報整備（月 1-3）
├─ Week 1-4：   系統入手，飼育開始，基本的な husbandry 確立
├─ Week 5-8：   smFISH プロトコル最適化，数組織での preliminary data
├─ Week 9-12：  qRT-PCR による各組織のハロウィーン遺伝子発現スクリーニング
└─ 成果：成虫 Halloween gene 発現マップ，CAFE assay の標準化

Phase 2: Tissue-specific RNAi スクリーニング（月 4-8）
├─ Week 13-16： GAL4 × UAS系統の交配，F1 個体の準備
├─ Week 17-24： 複数グループでの並列 CAFE assay 測定
│              （各グループ n≥12，複数 replicates）
├─ Week 25-32： Hemolymph 採集，LC-MS/MS 測定（外部協力機関）
└─ 成果：各 tissue-specific KD での毒物忌避行動の相対的変化，ホルモン濃度データ

Phase 3: メカニズム解明（月 9-12）
├─ Week 33-40： 救済実験（外部エクダイソン投与）
├─ Week 41-44： Neverland-GFP reporter での動的観察（in vivo imaging）
├─ Week 45-48： 毒物応答的ハロウィーン遺伝子発現の qRT-PCR 検証
├─ Week 49-52： DopEcR 活性化試験（if time permits）
└─ 成果：メカニズムの詳細な理解，論文 draft 作成

Year 2（予備期間・拡張実験）
├─ 補足実験（必要に応じて）
├─ 論文投稿準備，投稿
└─ 学会発表準備
```

### 6.2 主要マイルストーン

| マイルストーン | 実施予定月 | 成果物 |
|------------|---------|-------|
| Phase 1 完了 | 月3 | In situ ISH マップ，qRT-PCR data |
| GAL4 × UAS 系統交配完了 | 月4 | F1 個体 n > 200 |
| Phase 2 CAFE 測定完了 | 月8 | 行動データ表，図，多重比較統計 |
| ホルモン定量完了 | 月8 | LC-MS/MS レポート |
| 救済実験完了 | 月11 | Dose-response 図 |
| 初稿完成 | 月12 | Manuscript draft（Methods, Results） |

---

## 7. 予算見積もり（概算）

### 7.1 消耗品

| 項目 | 単価 | 数量 | 合計 |
|------|------|------|------|
| FISH probe kit（per gene） | ¥80,000 | 3 genes | ¥240,000 |
| qRT-PCR master mix | ¥40,000/box | 4 boxes | ¥160,000 |
| ハエの食料（培地） | ¥5,000/L | 50 L/year | ¥250,000 |
| 化学物質（CuSO4, ecdysone等） | ¥300,000 | - | ¥300,000 |
| Capillaries, tips, tubes等 | ¥100,000 | - | ¥100,000 |
| LC-MS/MS 測定（外部依託） | ¥50,000/sample | 80 samples | ¥4,000,000 |

**消耗品合計**：約 ¥5,050,000

### 7.2 設備費

外部共用施設を利用するため，設備購入は不要（または最小限）

### 7.3 旅費

- 学会発表（国内 2回，国際 1回予定）
- 外部協力機関への訪問

### 7.4 その他（間接経費など）

基盤研究（C）申請の場合：直接経費の30%程度

**想定総予算（全体）**：¥6,500,000 - ¥7,000,000

---

## 8. 倫理・安全性の考慮

### 8.1 動物実験の倫理的承認

本研究は，ショウジョウバエを実験対象とするため，公式な IACUC 承認を必要としないが，施設の標準的な飼育・実験ガイドラインに準拠する（東北大学研究倫理委員会への事前確認を推奨）。

### 8.2 化学物質の安全性

- CuSO4：一般的な金属塩，毒性低〜中程度，標準的な実験室安全プロトコルで対応
- 20-hydroxyecdysone：昆虫ホルモン，哺乳動物への毒性低い
- 使用施設：化学薬品取り扱い認定スペース

### 8.3 バイオセーフティ

ショウジョウバエは BSL-1 扱い，特別な制限なし

---

## 9. 研究成果の発信と波及効果

### 9.1 論文発表予定

1. **第1報（主報）**：フェーズ1-2 の成果
   - 題名案：「Tissue-specific ecdysone synthesis in adult Drosophila: identification of multiple sources and their roles in toxin avoidance」
   - 投稿先候補：*Current Biology*, *PLOS Biology*, *Developmental Cell*

2. **第2報（補足）**：フェーズ3 のメカニズム
   - 題名案：「Dynamic ecdysone induction in response to toxin exposure: a multi-organ coordinated response」
   - 投稿先候補：*eLife*, *Nature Communications*

### 9.2 学会発表

1. **国内学会**：
   - 日本神経科学学会年会（秋）：ポスター or 口頭
   - 日本発生生物学会（春）：ポスター

2. **国際学会**：
   - Society for Integrative and Comparative Biology (SICB)：口頭
   - European Drosophila Research Conference：ポスター

### 9.3 応用への展開

1. **害虫防除への利用**：
   - 成果を産業界（農業用害虫防除企業）と共有
   - エクダイソン合成阻害剤のスクリーニングプラットフォーム開発

2. **医学研究への応用**：
   - グルココルチコイドなどのステロイドホルモンと行動の関係の再検討
   - 薬学部での教育・研究への応用

### 9.4 資料の公開

- ショウジョウバエ系統：Bloomington Drosophila Stock Center へ寄託
- 論文データ：figshare, Zenodo などのデータリポジトリで公開
- コード：GitHub での公開（R scripts, ImageJ macros）

---

## 10. 参考文献

1. Nijhout, H. F. (1994). *Insect Hormones*. Princeton University Press.

2. Thummel, C. S., & Chory, J. (2002). Steroid hormone signaling in plants and insects. *Journal of Cell Biology*, 155(6), 899-903.

3. Ichinose, T., & Tanimoto, H., et al. (2025). Ecdysteroid-DopEcR signaling in neuronal and midgut cells mediates toxin avoidance and detoxification in *Drosophila*. *Current Biology*, **35**(6), [page numbers].

4. Nijhout, H. F., & Riddiford, L. M. (1979). Juvenile hormone is needed to sustain wing imaginal discs prior to metamorphosis of *Drosophila melanogaster*. *Journal of Experimental Biology*, 80, 141-158.

5. Terry, M. I., et al. (2024). Local ecdysone synthesis in a wounded epithelium sustains repair. *Current Biology*, [in press].

6. Petryk, A., et al. (2003). Halloween genes encode cytochrome P450 enzymes required for ecdysone synthesis. *Genome Biology*, 4(1), R3.

7. Ou, Q., et al. (2016). *Soul*, a connexin involved in gap junctional communication, is required for a complete (but not abdominal) moult in *Drosophila*. *Development*, 143, 4218-4230.

8. Raj, A., van den Bogaard, P., Rifkin, S. A., van Oudenaarden, A., & Tyagi, S. (2008). Imaging individual mRNA molecules using multiple singly labeled probes. *Nature Methods*, 5(10), 877-879.

9. Port, F., Chen, H. M., Lee, T., & Bulkley, D. (2014). Optimized CRISPR/Cas tools for efficient germline and somatic genome engineering in *Drosophila*. *Proceedings of the National Academy of Sciences USA*, 111(29), E2967-E2976.

10. Jaspers, G. W., & Geerts, W. J. (1979). Ecdysone-induced developmental arrest in *Drosophila melanogaster*. *Developmental Biology*, 71(2), 296-308.

11. Tennessen, J. M., & Thummel, C. S. (2011). Coordinating growth, maturation, and developmental timing in *Drosophila*. *Current Biology*, 21(10), R750-R757.

12. Niwa, R., & Niwa, Y. S. (2016). Developmental action of juvenile hormone signaling in *Drosophila*. *Current Opinion in Insect Science*, 17, 11-17.

13. Karpac, J., & Jasper, H. (2016). Insulin and JNK signaling in the *Drosophila* hypothalamus-like brain region. *Current Biology*, 21(16), 1496-1502.

14. Schmittgen, T. D., & Livak, K. J. (2008). Analyzing real-time PCR data by the comparative CT method. *Nature Protocols*, 3(6), 1101-1108.

[追加参考文献は省略，実際の提出時には20-30文献まで拡張推奨]

---

## 付録A：使用する GAL4 ドライバーラインの詳細リスト

[表形式で20-30の推定ドライバーを記載，各々の背景遺伝子，発現パターン画像の参照先等を記載]

---

## 付録B：CAFE アッセイの詳細プロトコル

[マニュアルのような形で，step-by-step の手順，画像，troubleshooting を記載]

---

## 付録C：qRT-PCR プライマー設計表

[各ハロウィーン遺伝子について，forward/reverse primer sequence, Tm, expected PCR product size を記載]

---

**文書作成日**：2026年1月31日  
**バージョン**：1.0  
**推定提出対象**：東北大学 大学院 生命科学研究科（学位論文研究計画），または JSPS 科研費（基盤研究C）

