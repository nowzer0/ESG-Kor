# ESG-Kor
This repository contains the resources introduced in the paper 'ESG-Kor: A Korean Dataset for ESG-related Information Extraction and Practical Use Cases,' presented at the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP). It supports ESG-related information extraction in the Korean context.


ESG-Kor is constructed using a Korean company's sustainability reports from the following sectors: Automobile, Aviation, Electronics, Finance, Heavy industry, Steel industry, and IT sector. Each sentence in the dataset was manually labeled, considering the criteria of global ESG evaluation agencies such as MSCI and Refinitiv, as well as the Korean corporate governance institute, Korea Corporate Governance Service (KCGS). The sentences were labeled into five classes: Environmental (E), Social (S), Governance (G), and Relevant (R), indicating the presence of ESG-related elements but not falling into specific E, S, or G categories, and Irrelevant (I) denoting sentences unrelated to ESG. ESG-Kor provides two tasks: multi-class classification for categorizing sentences into E, S, or G categories and binary-class classification for determining the ESG relevance of each sentence.


Various pre-trained language models based on the Korean language were fine-tuned using the ESG-Kor dataset, and the models demonstrated effective performance in performing the given tasks. This suggests that applying the ESG-Kor dataset to existing PLMs allows for proper extraction and classification of relevant information in the field of ESG of Korea, a specialized domain in a particular country. The process of constructing the ESG-Kordataset could serve as a benchmark for constructing ESG datasets in various countries.


ESG-Kor was created by [IDSL](https://sites.google.com/dm.snu.ac.kr/idsl/home) of Hanyang University in Republic of Korea. More information about ESG-Kor can be found in [ESG-Kor: A Korean Dataset for ESG-related Information Extraction and Practical Use Cases]().




## Examples of ESG-Kor
![ESG_Kor_fig1](https://github.com/user-attachments/assets/782c9f30-f234-432a-ba65-ff59cd976fd8)

## Datasets
|Class|Automobile|Aviation|Electroncis|Finance|Heavy industry|Steel industry|IT|Total|
|:-----:|:-----------:|:--------:|:----------:|:-------:|:---------------:|:--------------:|:-----:|:------:|
|E|5,783|1,727|4,511|2,228|1,779|3,701|60|19,789|
|S|8,466|3,946|9,033|12,578|5,693|5,802|264|45,782|
|G|896|463|1,928|3,014|751|1,690|77|8,819|
|R|972|825|337|1,566|957|996|51|5,704|
|I|8,958|2,363|7,789|8,355|4,429|6,697|261|38,852|
|Total|25,075|9,324|23,598|27,741|13,609|18,886|713|118,946|

## Citation
Will be released soon

## License
This project is licensed under the AFL v3.0 License - see the [LICENSE](https://github.com/nowzer0/ESG-Kor/blob/main/LICENSE) file for details.
