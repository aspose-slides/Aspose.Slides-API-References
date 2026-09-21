---
title: ICell class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/icell/
---
## ICell क्लास

टेबल में एक सेल का प्रतिनिधित्व करता है।

ICell प्रकार निम्न सदस्य जारी करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`offset_x`](/slides/python-net/hi/aspose.slides/icell/offset_x/) | टेबल की बाएँ ओर से सेल की बाएँ ओर तक की दूरी लौटाता है।<br/>            केवल पढ़ने योग्य **float**. |
| [`offset_y`](/slides/python-net/hi/aspose.slides/icell/offset_y/) | टेबल की ऊपर की ओर से सेल की ऊपर की ओर तक की दूरी लौटाता है।<br/>            केवल पढ़ने योग्य **float**. |
| [`first_row_index`](/slides/python-net/hi/aspose.slides/icell/first_row_index/) | सेल द्वारा कवर की गई पहली पंक्ति का सूचकांक लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`first_column_index`](/slides/python-net/hi/aspose.slides/icell/first_column_index/) | सेल द्वारा कवर किए गए पहले कॉलम का सूचकांक लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`width`](/slides/python-net/hi/aspose.slides/icell/width/) | सेल की चौड़ाई लौटाता है।<br/>            केवल पढ़ने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/icell/height/) | सेल की ऊंचाई लौटाता है।<br/>            केवल पढ़ने योग्य **float**. |
| [`minimal_height`](/slides/python-net/hi/aspose.slides/icell/minimal_height/) | सेल की न्यूनतम ऊंचाई लौटाता है।<br/>            यह सेल द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊंचाइयों का योग है।<br/>            केवल पढ़ने योग्य **float**. |
| [`margin_left`](/slides/python-net/hi/aspose.slides/icell/margin_left/) | TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`margin_right`](/slides/python-net/hi/aspose.slides/icell/margin_right/) | TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`margin_top`](/slides/python-net/hi/aspose.slides/icell/margin_top/) | TextFrame में शीर्ष मार्जिन लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`margin_bottom`](/slides/python-net/hi/aspose.slides/icell/margin_bottom/) | TextFrame में निचला मार्जिन लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`text_vertical_type`](/slides/python-net/hi/aspose.slides/icell/text_vertical_type/) | ऊर्ध्वाधर पाठ का प्रकार लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`TextVerticalType`](/slides/python-net/hi/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/hi/aspose.slides/icell/text_anchor_type/) | पाठ एंकर प्रकार लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`TextAnchorType`](/slides/python-net/hi/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/hi/aspose.slides/icell/anchor_center/) | निर्धारित करता है कि पाठ बॉक्स सेल के अंदर केंद्रित है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`first_column`](/slides/python-net/hi/aspose.slides/icell/first_column/) | सेल का पहला कॉलम प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IColumn`](/slides/python-net/hi/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/hi/aspose.slides/icell/first_row/) | सेल की पहली पंक्ति प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IRow`](/slides/python-net/hi/aspose.slides/irow). |
| [`col_span`](/slides/python-net/hi/aspose.slides/icell/col_span/) | पैरेंट टेबल की टेबल ग्रिड में ग्रिड कॉलमों की संख्या लौटाता है<br/>            जिसे वर्तमान सेल द्वारा विस्तारित किया जाएगा। यह गुण सेल्स को<br/>            मर्ज़ किए गए दिखने की अनुमति देता है, क्योंकि वे टेबल में अन्य सेल्स की लम्बवत सीमाओं को पार करते हैं।<br/>            केवल पढ़ने योग्य **int**. |
| [`row_span`](/slides/python-net/hi/aspose.slides/icell/row_span/) | मर्ज़ किए गए सेल द्वारा विस्तारित पंक्तियों की संख्या लौटाता है। यह अन्य सेल्स पर vMerge एट्रिब्यूट के साथ संयुक्त रूप से उपयोग किया जाता है ताकि एक क्षैतिज मर्ज़ की आरंभिक सेल को निर्दिष्ट किया जा सके।<br/>            केवल पढ़ने योग्य **int**. |
| [`text_frame`](/slides/python-net/hi/aspose.slides/icell/text_frame/) | सेल का टेक्स्ट फ्रेम लौटाता है।<br/>            केवल पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`table`](/slides/python-net/hi/aspose.slides/icell/table/) | सेल के लिए पैरेंट Table ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`ITable`](/slides/python-net/hi/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/hi/aspose.slides/icell/is_merged_cell/) | यदि सेल किसी भी समायोजित सेल के साथ मर्ज़ किया गया है तो true लौटाता है, अन्यथा false।<br/>            केवल पढ़ने योग्य **bool**. |
| [`cell_format`](/slides/python-net/hi/aspose.slides/icell/cell_format/) | इस सेल के फ़ॉर्मेटिंग गुणों को समाहित करने वाले CellFormat ऑब्जेक्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`ICellFormat`](/slides/python-net/hi/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/hi/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/icell/presentation/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/hi/aspose.slides/icell/split_by_col_span/#int) | कॉलम के सूचकांक द्वारा सेल को दो सेल्स में विभाजित करता है। |
| [`split_by_row_span(self, index)`](/slides/python-net/hi/aspose.slides/icell/split_by_row_span/#int) | पंक्ति के सूचकांक द्वारा सेल को दो सेल्स में विभाजित करता है। |
| [`split_by_height(self, height)`](/slides/python-net/hi/aspose.slides/icell/split_by_height/#float) | सेल को ऊँचाई के आधार पर विभाजित करता है। |
| [`split_by_width(self, width)`](/slides/python-net/hi/aspose.slides/icell/split_by_width/#float) | सेल को चौड़ाई के आधार पर विभाजित करता है। |

### अधिक देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)