---
title: PaperKind
second_title: Aspose.Slides for C++ API 레퍼런스
description: 표준 용지 크기를 지정합니다.
type: docs
weight: 144
url: /ko/system.drawing.printing/paperkind/
---
## PaperKind enum

표준 용지 크기를 지정합니다.

```cpp
enum class PaperKind
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Custom | 0 | 용지 크기는 사용자가 정의합니다. |
| Letter | 1 | 레터 용지 (8.5인치 x 11인치). |
| LetterSmall | 2 | 소형 레터 용지 (8.5인치 x 11인치). |
| Tabloid | 3 | 타블로이드 용지 (11인치 x 17인치). |
| Ledger | 4 | Ledger 용지 (17인치 x 11인치). |
| Legal | 5 | Legal 용지 (8.5인치 x 14인치). |
| Statement | 6 | Statement 용지 (5.5인치 x 8.5인치). |
| Executive | 7 | Executive 용지 (7.25인치 x 10.5인치). |
| A3 | 8 | A3 용지 (297 mm by 420 mm). |
| A4 | 9 | A4 용지 (210 mm by 297 mm). |
| A4Small | 10 | A4 소형 용지 (210 mm by 297 mm). |
| A5 | 11 | A5 용지 (148 mm by 210 mm). |
| B4 | 12 | B4 용지 (250 mm by 353 mm). |
| B5 | 13 | B5 용지 (176 mm by 250 mm). |
| Folio | 14 | Folio 용지 (8.5인치 x 13인치). |
| Quarto | 15 | Quarto 용지 (215 mm by 275 mm). |
| Standard10x14 | 16 | 표준 용지 (10인치 x 14인치). |
| Standard11x17 | 17 | 표준 용지 (11인치 x 17인치). |
| Note | 18 | 노트 용지 (8.5인치 x 11인치). |
| Number9Envelope | 19 | #9 봉투 (3.875인치 x 8.875인치). |
| Number10Envelope | 20 | #10 봉투 (4.125인치 x 9.5인치). |
| Number11Envelope | 21 | #11 봉투 (4.5인치 x 10.375인치). |
| Number12Envelope | 22 | #12 봉투 (4.75인치 x 11인치). |
| Number14Envelope | 23 | #14 봉투 (5인치 x 11.5인치). |
| CSheet | 24 | C 용지 (17인치 x 22인치). |
| DSheet | 25 | D 용지 (22인치 x 34인치). |
| ESheet | 26 | E 용지 (34인치 x 44인치). |
| DLEnvelope | 27 | DL 봉투 (110 mm by 220 mm). |
| C5Envelope | 28 | C5 봉투 (162 mm by 229 mm). |
| C3Envelope | 29 | C3 봉투 (324 mm by 458 mm). |
| C4Envelope | 30 | C4 봉투 (229 mm by 324 mm). |
| C6Envelope | 31 | C6 봉투 (114 mm by 162 mm). |
| C65Envelope | 32 | C65 봉투 (114 mm by 229 mm). |
| B4Envelope | 33 | B4 봉투 (250 mm by 353 mm). |
| B5Envelope | 34 | B5 봉투 (176 mm by 250 mm). |
| B6Envelope | 35 | B6 봉투 (176 mm by 125 mm). |
| ItalyEnvelope | 36 | 이탈리아 봉투 (110 mm by 230 mm). |
| MonarchEnvelope | 37 | Monarch 봉투 (3.875인치 x 7.5인치). |
| PersonalEnvelope | 38 | 6 3/4 봉투 (3.625인치 x 6.5인치). |
| USStandardFanfold | 39 | 미국 표준 팬폴드 (14.875인치 x 11인치). |
| GermanStandardFanfold | 40 | 독일 표준 팬폴드 (8.5인치 x 12인치). |
| GermanLegalFanfold | 41 | 독일 법적 팬폴드 (8.5인치 x 13인치). |
| IsoB4 | 42 | ISO B4 (250 mm by 353 mm). |
| JapanesePostcard | 43 | 일본 엽서 (100 mm by 148 mm). |
| Standard9x11 | 44 | 표준 용지 (9인치 x 11인치). |
| Standard10x11 | 45 | 표준 용지 (10인치 x 11인치). |
| Standard15x11 | 46 | 표준 용지 (15인치 x 11인치). |
| InviteEnvelope | 47 | 초대장 봉투 (220 mm by 220 mm). |
| LetterExtra | 50 | Letter extra 용지 (9.275인치 x 12인치). 이 값은 PostScript 드라이버에만 해당되며 Linotronic 프린터에서 용지를 절약하기 위해서만 사용됩니다. |
| LegalExtra | 51 | Legal extra 용지 (9.275인치 x 15인치). 이 값은 PostScript 드라이버에만 해당되며 Linotronic 프린터에서 용지를 절약하기 위해서만 사용됩니다. |
| TabloidExtra | 52 | Tabloid extra 용지 (11.69인치 x 18인치). 이 값은 PostScript 드라이버에만 해당되며 Linotronic 프린터에서 용지를 절약하기 위해서만 사용됩니다. |
| A4Extra | 53 | A4 extra 용지 (236 mm by 322 mm). 이 값은 PostScript 드라이버에만 해당되며 Linotronic 프린터에서 용지를 절약하는 데 도움이 됩니다. |
| LetterTransverse | 54 | Letter transverse 용지 (8.275인치 x 11인치). |
| A4Transverse | 55 | A4 transverse 용지 (210 mm by 297 mm). |
| LetterExtraTransverse | 56 | Letter extra transverse 용지 (9.275인치 x 12인치). |
| APlus | 57 | SuperA/SuperA/A4 용지 (227 mm by 356 mm). |
| BPlus | 58 | SuperB/SuperB/A3 용지 (305 mm by 487 mm). |
| LetterPlus | 59 | Letter plus 용지 (8.5인치 x 12.69인치). |
| A4Plus | 60 | A4 plus 용지 (210 mm by 330 mm). |
| A5Transverse | 61 | A5 transverse 용지 (148 mm by 210 mm). |
| B5Transverse | 62 | JIS B5 transverse 용지 (182 mm by 257 mm). |
| A3Extra | 63 | A3 extra 용지 (322 mm by 445 mm). |
| A5Extra | 64 | A5 extra 용지 (174 mm by 235 mm). |
| B5Extra | 65 | ISO B5 extra 용지 (201 mm by 276 mm). |
| A2 | 66 | A2 용지 (420 mm by 594 mm). |
| A3Transverse | 67 | A3 transverse 용지 (297 mm by 420 mm). |
| A3ExtraTransverse | 68 | A3 extra transverse 용지 (322 mm by 445 mm). |
| JapaneseDoublePostcard | 69 | 일본 이중 엽서 (200 mm by 148 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| A6 | 70 | A6 용지 (105 mm by 148 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeKakuNumber2 | 71 | Japanese Kaku #2 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeKakuNumber3 | 72 | Japanese Kaku #3 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeChouNumber3 | 73 | Japanese Chou #3 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeChouNumber4 | 74 | Japanese Chou #4 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| LetterRotated | 75 | Letter rotated 용지 (11인치 x 8.5인치). |
| A3Rotated | 76 | A3 rotated 용지 (420 mm by 297 mm). |
| A4Rotated | 77 | A4 rotated 용지 (297 mm by 210 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| A5Rotated | 78 | A5 rotated 용지 (210 mm by 148 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| B4JisRotated | 79 | JIS B4 rotated 용지 (364 mm by 257 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| B5JisRotated | 80 | JIS B5 rotated 용지 (257 mm by 182 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapanesePostcardRotated | 81 | Japanese rotated 엽서 (148 mm by 100 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseDoublePostcardRotated | 82 | Japanese rotated 이중 엽서 (148 mm by 200 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| A6Rotated | 83 | A6 rotated 용지 (148 mm by 105 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeKakuNumber2Rotated | 84 | Japanese rotated Kaku #2 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeKakuNumber3Rotated | 85 | Japanese rotated Kaku #3 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeChouNumber3Rotated | 86 | Japanese rotated Chou #3 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeChouNumber4Rotated | 87 | Japanese rotated Chou #4 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| B6Jis | 88 | JIS B6 용지 (128 mm by 182 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| B6JisRotated | 89 | JIS B6 rotated 용지 (182 mm by 128 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| Standard12x11 | 90 | 표준 용지 (12인치 x 11인치). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeYouNumber4 | 91 | Japanese You #4 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| JapaneseEnvelopeYouNumber4Rotated | 92 | Japanese You #4 rotated 봉투. 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| Prc16K | 93 | 16K 용지 (146 mm by 215 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| Prc32K | 94 | 32K 용지 (97 mm by 151 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| Prc32KBig | 95 | 32K big 용지 (97 mm by 151 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber1 | 96 | #1 봉투 (102 mm by 165 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber2 | 97 | #2 봉투 (102 mm by 176 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber3 | 98 | #3 봉투 (125 mm by 176 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber4 | 99 | #4 봉투 (110 mm by 208 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber5 | 100 | #5 봉투 (110 mm by 220 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 또는 이후. |
| PrcEnvelopeNumber6 | 101 | #6 봉투 (120 mm by 230 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber7 | 102 | #7 봉투 (160 mm by 230 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber8 | 103 | #8 봉투 (120 mm by 309 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber9 | 104 | #9 봉투 (229 mm by 324 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber10 | 105 | #10 봉투 (324 mm by 458 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| Prc16KRotated | 106 | 16K rotated 용지 (146 mm by 215 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| Prc32KRotated | 107 | 32K rotated 용지 (97 mm by 151 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| Prc32KBigRotated | 108 | 32K big rotated 용지 (97 mm by 151 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber1Rotated | 109 | #1 rotated 봉투 (165 mm by 102 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber2Rotated | 110 | #2 rotated 봉투 (176 mm by 102 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber3Rotated | 111 | #3 rotated 봉투 (176 mm by 125 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber4Rotated | 112 | #4 rotated 봉투 (208 mm by 110 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber5Rotated | 113 | Envelope #5 rotated 봉투 (220 mm by 110 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber6Rotated | 114 | #6 rotated 봉투 (230 mm by 120 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber7Rotated | 115 | #7 rotated 봉투 (230 mm by 160 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber8Rotated | 116 | #8 rotated 봉투 (309 mm by 120 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber9Rotated | 117 | #9 rotated 봉투 (324 mm by 229 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |
| PrcEnvelopeNumber10Rotated | 118 | #10 rotated 봉투 (458 mm by 324 mm). 필요: [Windows](../../system.windows/) 98, [Windows](../../system.windows/) NT 4.0, 및 이후. |

## 참고

* 네임스페이스 [System::Drawing::Printing](../)
* 라이브러리 [Aspose.Slides](../../)