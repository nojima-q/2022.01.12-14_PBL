# がん研究会PBL　シラバス　〜ゲノム解析〜

## 日時

2022年3月22日(火)、23日(水)、24日(木)のいずれか２日間の13時−17時


## 場所
研究所4階　435セミナー室 (基本的にzoom開催ですが、期間中、講師の先生がおられる435セミナー室でも（密にならない範囲で）受講可能です。また、エラー等が遠隔で解消できない時には、直接指導を受けることができます)。

## 講義の概要と学習目標
ゲノムシーケンスデータを参照ゲノムと比較し、どの染色体のどのポジションに変異が存在するか解析し可視化する。


## 用意するもの
コンピュータ１台


## 環境
OS：Mac（推奨）、Linux、Windows\
※チュートリアルは、Mac環境を前提として記載していますので、Macユーザーはほぼチュートリアルのコピーアンドペーストで実行できます。\
※Windows・Linuxの場合は書き換えが必要ですので、できるだけMacで実行して下さい。

## 使用するツール
### 端末上で操作
SRA Toolkit (https://github.com/ncbi/sra-tools/wiki/01.-Downloading-SRA-Toolkit) \
FastQC (https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) \
Trimmomatic (http://www.usadellab.org/cms/?page=trimmomatic) \
bwa (http://bio-bwa.sourceforge.net/) \
Samtools (http://www.htslib.org/) \
GATK (https://gatk.broadinstitute.org/hc/en-us) \
Picard (https://broadinstitute.github.io/picard/) \
VCFtools (http://vcftools.sourceforge.net/) \
PLINK (https://www.cog-genomics.org/plink/)
### RStudio上で操作
```
install.packages("dplyr")
install.packages("ggplot2")
install.packages("ggrepel")
```

## スケジュール
１日目：各種ツールのインストール、下記解析計画のチュートリアル\
２日目：自主学習 \
３日目：チュートリアルに従って、各自取得データを解析

## 解析計画
### 第一部（担当講師：大阪大学 野島）
1	公共データベースの紹介、データの取得方法\
2	FASTQファイルの形式、クオリティーコントロールについて\
3	アダプターの除去およびリードのトリミング\
4	リファレンスゲノムファイルの取得\
5	リファレンスゲノムへのマッピング\
6	マッピングデータの各種QC処理\
7 QC処理後データのvariant calling\
8 関連解析と各種解析結果の表示

### 第二部（担当講師：大阪大学 下川）
系統樹解析
## 講義資料・チュートリアル
https://github.com/nojima-q/2022.01.12-14_PBL_analysis
