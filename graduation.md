<!-- preview : control + shift + M -->

<!--
git status 確認
git diff (shift + Z) X 2 差分
git add . 追加
git status 確認
git commit -m "hogehoge message" コミット（ローカル）
git push origin master プッシュ
 -->

# 卒業論文 + 卒業制作について  

「アルゴリズムやジェネラティブなど、生成的な設計について」

&nbsp;  
&nbsp;  

## 先行研究  
- ### アルゴリズミック・デザイン （日本建築学会 編）  
渡辺誠 など  

- ### any シリーズ  
磯崎新、ピーター・アイゼンマン、グレッグ・リン など  
- ### パラメトリシズム  
パトリックシューマッハ

&nbsp;  
&nbsp;  

## 卒論から卒制に向けた流れ  
&nbsp;  
<-- ここから卒論 -->
  #### ジェネ系資料の洗い出し  
  - アルゴリズミック・デザイン （日本建築学会 編） // 今ここ  
  - Rhinoceros add-on Forum  
  - shape optimization tech by autodesk  

  #### 理論、アルゴリズムの検討  
  - グレッグ・リンのエッセイ // 読みにくい  
  - パラメトリシズム // 英語文献

<-- ここまで卒論 -->  

&nbsp;

  <-- ここから卒制 -->  
  #### 実装  
  - 先に起こったリサーチに基づき、 C# 、 C++ もしく Python でツールキット（ライブラリ）化する  


<-- ここまで卒制 -->  

&nbsp;  
&nbsp;  

##  ジェネ系資料の洗い出しより  
&nbsp;

- アルゴリズミック・デザイン （日本建築学会 編）  
  - 渡辺誠  
    - 「アルゴリズミックデザイン」とは、要求される課題を解くためのアルゴリズムを用い、解答として形態や構成を生成する、設計手法である  
    - 「生成」とは、アルゴリズム→プログラムを通じて「間接的に」成果物を「生み出す」  
    - 検証可能性、計測可能性  
    - 目的をかなえるためには、どういう手順で何をしたらいいのか  
    - 生成 + 評価のフィードバック回路

  - 五十嵐太郎  
    - アルゴリズムは関数として表現される規範性を持つとともに、パラメータの入力によって多様な差異をもたらす(柄沢祐輔)  
    - アルゴリズム的思考は、モダンの規範性とポストモダンの求めた多様性をともに可能とする、全く新しい文化的なフェイズへと私たちを導く(柄沢祐輔)  
    - 磯崎新と佐々木睦朗のフラックス・ストラクチャーになると、生物と工学の融合として流動的な構造が語られる  

  - 渡辺誠  
    - 「アルゴリズミック・デザイン」の内容は、曖昧性なく説明できる
    - 多義的なことばも衒学的な表現も、文学的レトリックも必要ない。（中略）そうして裸に近くなった姿が、アルゴリズムの本体だ。  
    - 設計者は多義と比喩でおられた布をまとうことを好む。  

  - 実作
    - 「コーポラ」 double Negative Architecture  
      - 工法・構造上の条件を満たし、変化のある壁面家具  
      - 施工上の可能範囲、強度上の可能な範囲  
      - 極座標系の空間表記法（Super eye）  

    ![dNA](photo/Resize-dNA-01.jpg)  
&nbsp;

    - 「神奈川工科大学 KAIT工房」 石上純也  
      - 柱の角度分布のグラフ表示や、3D表記。その結果を渡し、構造計算を行い、その結果を表示する。  
      - 恣意性と偶然性と合理性を、あるバランスで兼ね備えた建築を作れる可能性を示す。  

    ![KAIT](photo/Resize-Ishigami-01.jpg)  

&nbsp;


    - 「台中メトロポリタンオペラハウス」 伊東豊雄  
      - 直交グリッドをもとにしながら、その整形性の制約を超える空間形態を目指す。（ゲント同様）  
      - 3次元グリッド内での、指定条件に適合した滑らかな曲面形態（空間）の決定  
      - 生成する曲面は自由曲面ではなくカテノイドとすることで、全体形態に自由度とともに一貫性を与えている。  

    ![opera](photo/Resize-Ito-01.jpg)  


&nbsp;
&nbsp;



- Rhinoceros add-on Forum  
  - [kangaroo (physic sim)](http://www.grasshopper3d.com/group/kangaroo)  
    - hoge
  - [millipdede (optimization)](http://www.grasshopper3d.com/group/millipede)  
    - hoge
- shape optimization tech by autodesk  
  - [what is](https://www.autodesk.com/solutions/generative-design)  
    - [test (Fusion360)](https://www.youtube.com/watch?v=ItiezmZg5cY)


