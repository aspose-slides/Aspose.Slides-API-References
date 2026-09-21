---
title: Chart class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chart/
---
## Chart वर्ग

एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।

**विरासत:**[`Chart`](/slides/python-net/hi/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

Chart प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुण

| संपत्ति | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides.charts/chart/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>            केवल- पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides.charts/chart/placeholder/) | आकार के प्लेसहोल्डर को लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल- पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides.charts/chart/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल- पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides.charts/chart/raw_frame/) | रॉ आकार फ्रेम की विशेषताओं को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides.charts/chart/frame/) | आकार फ्रेम की विशेषताओं को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides.charts/chart/line_format/) | आकार के लिए लाइन फ़ॉर्मेट गुणधर्मों को समाहित करने वाला LineFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ आकार प्रकारों के लिये None लौटाया जा सकता है जिनमें लाइन गुणधर्म नहीं होते हैं।<br/>            केवल- पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides.charts/chart/three_d_format/) | आकार के लिए 3D इफ़ेक्ट गुणधर्मों को समाहित करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ आकार प्रकारों के लिये None लौटाया जा सकता है जिनमें 3D गुणधर्म नहीं होते हैं।<br/>            केवल- पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides.charts/chart/effect_format/) | आकार पर लागू पिक्सेल इफ़ेक्ट्स को समाहित करने वाला EffectFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ आकार प्रकारों के लिये None लौटाया जा सकता है जिनमें इफ़ेक्ट गुणधर्म नहीं होते हैं।<br/>            केवल- पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides.charts/chart/fill_format/) | आकार के लिए भराव फ़ॉर्मेट गुणधर्मों को समाहित करने वाला FillFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ आकार प्रकारों के लिये None लौटाया जा सकता है जिनमें भराव गुणधर्म नहीं होते हैं।<br/>            केवल- पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides.charts/chart/hyperlink_click/) | माउस क्लिक के लिये परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides.charts/chart/hyperlink_mouse_over/) | माउस ओवर के लिये परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides.charts/chart/hyperlink_manager/) | हाइपरलिंक प्रबंधनकर्ता को लौटाता है।<br/>            केवल- पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides.charts/chart/hidden/) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides.charts/chart/z_order_position/) | आकार की z-क्रम में स्थिति को लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे वाले आकार को लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-क्रम के आगे वाले आकार को लौटाता है।<br/>            केवल- पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides.charts/chart/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या को लौटाता है।<br/>            केवल- पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides.charts/chart/rotation/) | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या को लौटाता या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगामी घूर्णन दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides.charts/chart/x/) | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापते हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.charts/chart/y/) | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापते हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.charts/chart/width/) | आकार की चौड़ाई को पॉइंट्स में मापते हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.charts/chart/height/) | आकार की ऊँचाई को पॉइंट्स में मापते हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides.charts/chart/black_white_mode/) | गुणधर्म निर्धारित करता है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides.charts/chart/unique_id/) | ऐड-इन या अन्य कोड द्वारा उपयोग के लिये अभिप्रेत एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी विशिष्ट कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल- पढ़ने योग्य **int**।<br/>            देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides.charts/chart/office_interop_shape_id/) | स्लाइड-स्कोप्ड विशिष्ट पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल- पढ़ने योग्य **int**।<br/>            देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides.charts/chart/alternative_text/) | आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides.charts/chart/alternative_text_title/) | आकार से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides.charts/chart/name/) | आकार का नाम लौटाता या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का प्रयोग करें।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides.charts/chart/is_decorative/) | ‘Mark as decorative’ विकल्प को प्राप्त करता या सेट करता है<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides.charts/chart/shape_lock/) | आकार के लॉक लौटाता है।<br/>            केवल- पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides.charts/chart/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>            केवल- पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides.charts/chart/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल- पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/chart/slide/) | आकार की पैरेंट स्लाइड को लौटाता है।<br/>            केवल- पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/chart/presentation/) | स्लाइड की पैरेंट प्रेजेंटेशन को लौटाता है।<br/>            केवल- पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides.charts/chart/graphical_object_lock/) | आकार के लॉक लौटाता है।<br/>            केवल- पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/hi/aspose.slides.charts/chart/plot_visible_cells_only/) | निर्धारित करता है कि केवल दृश्यमान कोशिकाओं को ही प्लॉट किया जाए। दोनों दृश्यमान और छिपी कोशिकाओं को प्लॉट करने के लिये False सेट करें।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`display_blanks_as`](/slides/python-net/hi/aspose.slides.charts/chart/display_blanks_as/) | चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`DisplayBlanksAsType`](/slides/python-net/hi/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/hi/aspose.slides.charts/chart/chart_data/) | चार्ट से जुड़ी लिंक्ड या एम्बेडेड डेटा की जानकारी लौटाता है।<br/>            केवल- पढ़ने योग्य [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/hi/aspose.slides.charts/chart/has_title/) | निर्धारित करता है कि चार्ट का शीर्षक दृश्यमान है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`chart_title`](/slides/python-net/hi/aspose.slides.charts/chart/chart_title/) | चार्ट शीर्षक लौटाता या सेट करता है।<br/>            केवल- पढ़ने योग्य [`IChartTitle`](/slides/python-net/hi/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/hi/aspose.slides.charts/chart/has_data_table/) | निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`has_legend`](/slides/python-net/hi/aspose.slides.charts/chart/has_legend/) | निर्धारित करता है कि चार्ट में लेजेंड है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`legend`](/slides/python-net/hi/aspose.slides.charts/chart/legend/) | चार्ट के लिए लेजेंड लौटाता या सेट करता है।<br/>            केवल- पढ़ने योग्य [`ILegend`](/slides/python-net/hi/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/hi/aspose.slides.charts/chart/chart_data_table/) | चार्ट की डेटा तालिका लौटाता है।<br/>            केवल- पढ़ने योग्य [`IDataTable`](/slides/python-net/hi/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/hi/aspose.slides.charts/chart/style/) | चार्ट शैली लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`StyleType`](/slides/python-net/hi/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/hi/aspose.slides.charts/chart/type/) | चार्ट प्रकार लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/hi/aspose.slides.charts/chart/plot_area/) | चार्ट के प्लॉट एरिया को दर्शाता है।<br/>            केवल- पढ़ने योग्य [`IChartPlotArea`](/slides/python-net/hi/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/hi/aspose.slides.charts/chart/rotation_3d/) | चार्ट की 3D घूर्णन लौटाता है।<br/>            केवल- पढ़ने योग्य [`IRotation3D`](/slides/python-net/hi/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/hi/aspose.slides.charts/chart/back_wall/) | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वॉल की फ़ॉर्मेट बदलने की अनुमति देता है।<br/>            केवल- पढ़ने योग्य [`IChartWall`](/slides/python-net/hi/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/hi/aspose.slides.charts/chart/side_wall/) | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइड वॉल की फ़ॉर्मेट बदलने की अनुमति देता है।<br/>            केवल- पढ़ने योग्य [`IChartWall`](/slides/python-net/hi/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/hi/aspose.slides.charts/chart/floor/) | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर की फ़ॉर्मेट बदलने की अनुमति देता है।<br/>            केवल- पढ़ने योग्य [`IChartWall`](/slides/python-net/hi/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/chart/text_format/) | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है।<br/>            यह गुण निम्नलिखित प्रकारों के लिये लागू नहीं है: [`ChartType.TREEMAP`](/slides/python-net/hi/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/hi/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/hi/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/hi/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/hi/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/hi/aspose.slides.charts/charttype/BOX_AND_WHISKER)।<br/>            केवल- पढ़ने योग्य [`IChartTextFormat`](/slides/python-net/hi/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/hi/aspose.slides.charts/chart/theme_manager/) | थीम मैनेजर लौटाता है।<br/>            केवल- पढ़ने योग्य [`IOverrideThemeManager`](/slides/python-net/hi/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/hi/aspose.slides.charts/chart/user_shapes/) | चार्ट के ऊपर खींचे जाने वाले आकारों को निर्दिष्ट करता है।<br/>            केवल- पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/hi/aspose.slides.charts/chart/axes/) | चार्ट अक्षों तक पहुंच प्रदान करता है।<br/>            केवल- पढ़ने योग्य [`IAxesManager`](/slides/python-net/hi/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/hi/aspose.slides.charts/chart/show_data_labels_over_maximum/) | निर्धारित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`has_rounded_corners`](/slides/python-net/hi/aspose.slides.charts/chart/has_rounded_corners/) | निर्धारित करता है कि चार्ट क्षेत्र के किनारे गोल हों।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/chart/chart/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides.charts/chart/get_image/#) | आकार थंबनेल लौटाता है।<br/>            ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides.charts/chart/remove_placeholder/#) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणधर्मों को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides.charts/chart/get_base_placeholder/#) | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार इनहेरिट किया गया है)।<br/>            यदि वर्तमान आकार इनहेरिट नहीं किया गया है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides.charts/chart/get_visual_bounds/#) | आकार की दृश्य सीमा को उसके रेंडर किए गए कंटेंट से गणना कर प्राप्त करता है। |
| [`validate_chart_layout(self)`](/slides/python-net/hi/aspose.slides.charts/chart/validate_chart_layout/#) | चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थिति शामिल है जो IActualLayout इंटरफ़ेस को इम्प्लीमेंट करते हैं <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            और वास्तविक अक्ष मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides.charts/chart/create_theme_effective/#) | इस चार्ट के लिए प्रभावी थीम लौटाता है। |

### देखें भी
* वर्ग [`Chart`](/slides/python-net/hi/aspose.slides.charts/chart)
* वर्ग [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* वर्ग [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)