---
title: ExcelDataWorkbook class
second_title: Aspose.Slides के लिए Python के द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook क्लास

एक वर्कबुक का प्रतिनिधित्व करता है जो सामान्य उपयोग के लिए Excel डेटा तक पहुंच प्रदान करता है।

ExcelDataWorkbook प्रकार निम्नलिखित सदस्य प्रस्तुत करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/__init__/#str) | निर्दिष्ट फ़ाइल पथ का उपयोग करके एक नया उदाहरण प्रारंभ करता है। |
| [`__init__(self, stream)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | प्रदान किए गए स्ट्रीम का उपयोग करके वर्ग का नया उदाहरण प्रारंभ करता है। |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | निर्दिष्ट कार्यपत्रक से उसके सूचकांक और सेल समन्वय का उपयोग करके एक सेल प्राप्त करता है। |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | निर्दिष्ट कार्यपत्रक से उसके नाम और सेल समन्वय का उपयोग करके एक सेल प्राप्त करता है। |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | निर्दिष्ट कार्यपत्रक से उसके सूचकांक और Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है। |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके निर्दिष्ट कार्यपत्रक से एक सेल प्राप्त करता है। |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | वर्कबुक से उन कोशिकाओं का संग्रह प्राप्त करता है जो निर्दिष्ट सूत्र से मेल खाती हैं। |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Excel वर्कबुक के निर्दिष्ट कार्यपत्रक में सभी चार्ट के सूचकांक और नामों वाली एक शब्दकोश प्राप्त करता है। |
| [`get_worksheet_names(self)`](/slides/python-net/hi/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Excel वर्कबुक में सम्मिलित सभी कार्यपत्रकों के नाम प्राप्त करता है। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides.excel`](/slides/python-net/hi/aspose.slides.excel)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)