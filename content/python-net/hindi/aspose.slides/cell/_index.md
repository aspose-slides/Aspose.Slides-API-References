---
title: Cell class
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/cell/
---
## Cell क्लास

एक तालिका की कोशिका का प्रतिनिधित्व करता है।

Cell प्रकार निम्नलिखित सदस्यों को प्रस्तुत करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`offset_x`](/slides/python-net/hi/aspose.slides/cell/offset_x/) | एक तालिका के बाएँ पक्ष से कोशिका के बाएँ पक्ष तक की दूरी लौटाता है.<br/>            केवल-पढ़ने योग्य **float**. |
| [`offset_y`](/slides/python-net/hi/aspose.slides/cell/offset_y/) | एक तालिका के शीर्ष पक्ष से कोशिका के शीर्ष पक्ष तक की दूरी लौटाता है.<br/>            केवल-पढ़ने योग्य **float**. |
| [`first_row_index`](/slides/python-net/hi/aspose.slides/cell/first_row_index/) | कोशिका द्वारा कवर की गई पहली पंक्ति का अनुक्रमांक लौटाता है.<br/>            केवल-पढ़ने योग्य **int**. |
| [`first_column_index`](/slides/python-net/hi/aspose.slides/cell/first_column_index/) | कोशिका द्वारा कवर किए गए पहले कॉलम का अनुक्रमांक लौटाता है.<br/>            केवल-पढ़ने योग्य **int**. |
| [`width`](/slides/python-net/hi/aspose.slides/cell/width/) | कोशिका की चौड़ाई लौटाता है.<br/>            केवल-पढ़ने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/cell/height/) | कोशिका की ऊँचाई लौटाता है.<br/>            केवल-पढ़ने योग्य **float**. |
| [`minimal_height`](/slides/python-net/hi/aspose.slides/cell/minimal_height/) | कोशिका द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग लौटाता है.<br/>            केवल-पढ़ने योग्य **float**. |
| [`margin_left`](/slides/python-net/hi/aspose.slides/cell/margin_left/) | TextFrame में बाएँ मार्जिन को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें **float**. |
| [`margin_right`](/slides/python-net/hi/aspose.slides/cell/margin_right/) | TextFrame में दाएँ मार्जिन को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें **float**. |
| [`margin_top`](/slides/python-net/hi/aspose.slides/cell/margin_top/) | TextFrame में शीर्ष मार्जिन को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें **float**. |
| [`margin_bottom`](/slides/python-net/hi/aspose.slides/cell/margin_bottom/) | TextFrame में निचला मार्जिन को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें **float**. |
| [`text_vertical_type`](/slides/python-net/hi/aspose.slides/cell/text_vertical_type/) | ऊर्ध्वाधर पाठ के प्रकार को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें [`TextVerticalType`](/slides/python-net/hi/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/hi/aspose.slides/cell/text_anchor_type/) | पाठ एंकर प्रकार को लौटाता है या सेट करता है.<br/>            पढ़ें/लिखें [`TextAnchorType`](/slides/python-net/hi/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/hi/aspose.slides/cell/anchor_center/) | निर्धारित करता है कि क्या पाठ बॉक्स कोशिका के भीतर केंद्रित है.<br/>            पढ़ें/लिखें **bool**. |
| [`first_row`](/slides/python-net/hi/aspose.slides/cell/first_row/) | कोशिका की पहली पंक्ति प्राप्त करता है.<br/>            केवल-पढ़ने योग्य [`IRow`](/slides/python-net/hi/aspose.slides/irow). |
| [`first_column`](/slides/python-net/hi/aspose.slides/cell/first_column/) | कोशिका का पहला कॉलम प्राप्त करता है.<br/>            केवल-पढ़ने योग्य [`IColumn`](/slides/python-net/hi/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/hi/aspose.slides/cell/col_span/) | माता तालिका के ग्रिड में ग्रिड कॉलमों की संख्या लौटाता है जो वर्तमान कोशिका द्वारा विस्तारित होगी. यह गुण कोशिकाओं को एक साथ मिलाने जैसा दिखावे देता है, क्योंकि वे तालिका में अन्य कोशिकाओं की ऊर्ध्वाधर सीमा को विस्तारित करते हैं.<br/>            केवल-पढ़ने योग्य **int**. |
| [`row_span`](/slides/python-net/hi/aspose.slides/cell/row_span/) | एक मर्ज की गई कोशिका द्वारा विस्तारित पंक्तियों की संख्या लौटाता है. यह अन्य कोशिकाओं पर vMerge विशेषता के साथ संयोजन में उपयोग किया जाता है ताकि क्षैतिज मर्ज की प्रारंभिक कोशिका निर्दिष्ट की जा सके.<br/>            केवल-पढ़ने योग्य **int**. |
| [`text_frame`](/slides/python-net/hi/aspose.slides/cell/text_frame/) | कोशिका का टेक्स्ट फ्रेम लौटाता है.<br/>            केवल-पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`table`](/slides/python-net/hi/aspose.slides/cell/table/) | कोशिका के लिए पैरेंट Table ऑब्जेक्ट लौटाता है.<br/>            केवल-पढ़ने योग्य [`ITable`](/slides/python-net/hi/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/hi/aspose.slides/cell/is_merged_cell/) | यदि कोशिका किसी समायोजित कोशिका के साथ मर्ज की गई है तो true लौटाता है, अन्यथा false.<br/>            केवल-पढ़ने योग्य **bool**. |
| [`cell_format`](/slides/python-net/hi/aspose.slides/cell/cell_format/) | CellFormat ऑब्जेक्ट लौटाता है जो इस कोशिका के फ़ॉर्मेटिंग गुणों को सम्मिलित करता है.<br/>            केवल-पढ़ने योग्य [`ICellFormat`](/slides/python-net/hi/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/hi/aspose.slides/cell/slide/) | कोशिका का पैरेंट स्लाइड लौटाता है.<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/cell/presentation/) | कोशिका की पैरेंट प्रस्तुति (presentation) लौटाता है.<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/hi/aspose.slides/cell/split_by_col_span/#int) | इंडेक्स ऑफ कॉलम द्वारा कोशिका को दो कोशिकाओं में विभाजित करता है. |
| [`split_by_row_span(self, index)`](/slides/python-net/hi/aspose.slides/cell/split_by_row_span/#int) | इंडेक्स ऑफ रो द्वारा कोशिका को दो कोशिकाओं में विभाजित करता है. |
| [`split_by_height(self, height)`](/slides/python-net/hi/aspose.slides/cell/split_by_height/#float) | ऊँचाई द्वारा कोशिका को विभाजित करता है. |
| [`split_by_width(self, width)`](/slides/python-net/hi/aspose.slides/cell/split_by_width/#float) | चौड़ाई द्वारा कोशिका को विभाजित करता है. |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)