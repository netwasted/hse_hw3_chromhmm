# hse_hw3_chromhmm

## HSE Bioinformatics HW 3

### Ссылка на Colab:

https://colab.research.google.com/drive/1HIAOEMfJkgf1sxexXTzTosAYzi-DwjZ-?usp=sharing

### Таблица гистоновых меток и соответствующих файлов

| Гистоновая метка | Имя файла         |
|------------------|-------------------|
| H2az             | K562_H2az.bam     |
| H3k27ac          | K562_H3k27ac.bam  |
| H3k27me3         | K562_H3k27me3.bam |
| H3k36me3         | K562_H3k36me3.bam |
| H3k4me1          | K562_H3k4me1.bam  |
| H3k4me2          | K562_H3k4me2.bam  |
| H3k4me3          | K562_H3k4me3.bam  |
| H3k79me2         | K562_H3k79me2.bam |
| H3k9ac           | K562_H3k9ac.bam   |
| H3k9me1          | K562_H3k9me1.bam  |

### Картинки из выдачи ChromHMM

![emissions_10](https://user-images.githubusercontent.com/60008375/160094484-5a13805c-614c-4559-a729-6e49c5e8b303.png)
![K562_10_overlap](https://user-images.githubusercontent.com/60008375/160094508-e3d81a6b-28a4-4905-8731-f4046af0faa0.png)
![K562_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/60008375/160094524-c33f36e2-7bce-4365-ad10-336aaa8bf3bb.png)
![K562_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/60008375/160094545-628dd3a8-a4a3-4aed-91d2-aa19977b5ebb.png)
![transitions_10](https://user-images.githubusercontent.com/60008375/160094556-4d6d4e93-4c43-46f2-b189-5f76b702ff91.png)

### Скриншоты из UCSC Genome Browser

![image](https://user-images.githubusercontent.com/60008375/160096335-8e4b336a-e0ca-4c7e-bb78-985a160caf24.png)

![image](https://user-images.githubusercontent.com/60008375/160097013-19bc61e5-364c-48bf-9c9d-f0c738e5a2b7.png)

### Таблица с названиями эпигенетических типов

| Номер эпигенетического типа | Присвоенное название | Характерная метка | Другие свойства                                                                      |
|-----------------------------|----------------------|-------------------|--------------------------------------------------------------------------------------|
| 1                           | Transcribed          | H3K36me3, H3K27ac | Попадает на гены. Слабый сигнал                                                      |
| 2                           | Heterochromatin      | -                 | Самый частовстречающийся тип в геноме.  Нет  четкой корреляции с определенной меткой |
| 3                           | Transcriptional      | H3K36m3           | Попадает на ген, сильный сигнал                                                      |
| 4                           | Transcriptional      | H3K79m2           | Сильный сигнал                                                                       |
| 5                           | Promoter             | H3K27ac, H3K4m*   | Сильный сигнал                                                                       |
| 6                           | Repressed            | -                 | Слабый сигнал                                                                        |
| 7                           | Enchancer            | H3K4m*, H2AFZ     | Сильный сигнал                                                                       |
| 8                           | Enchancer            | H2AFZ             | Может как попадать, так и не попадать на ген. Сигнал сильный                         |
| 9                           | Promoter             | H3K4m*            | В начале генов. Сигнал средний                                                       |
| 10                          | Enchancer            | Почти все         | Сильный сигнал                                                                       |

### Результат бонусного задания
