# BERT-for-question-answering-on-DRCD-dataset

* Task : Question Answering
* Model : bert-based-chinese
* Dataset : DRCD dataset

* DRCD
 ＞ * Delta Reading Comprehension Dataset
 ＞ * 台達閱讀理解資料集 Delta Reading Comprehension Dataset (DRCD) 屬於通用領域繁體中文機器閱讀理解資料集。 本資料集期望成為適用於遷移學習之標準中文閱讀理解資料集。 本資料集從2,108篇維基條目中整理出10,014篇段落，並從段落中標註出30,000多個問題

 * 關於資料集之更詳細資訊請洽詢論文： For more information please refer to Paper <https://arxiv.org/abs/1806.00920>
 * 格式:
   * version : 資料集版本
   * data :
     * title : : 文章標題
     * id : : 文章編號
     * paragraphs :
       * id : : 文章編號_段落編號
       * context : : 段落內容
       * qas :
         * question : : 問題內容
         * id : : 文章編號_段落編號_問題編號
         * answers :
           * answer_start : text在文中位置
           * id : : "1"表示為人工標註的答案，"2"以上為人工答題的答案
           * text : : 答案內容

* code: [colab](https://colab.research.google.com/drive/17YVCFm0m_JU7BuiliZIsH6LbQDgB1wbX)

* References:
  * [BERT](https://arxiv.org/pdf/1810.04805.pdf)
  * [DRCD](https://arxiv.org/ftp/arxiv/papers/1806/1806.00920.pdf)
