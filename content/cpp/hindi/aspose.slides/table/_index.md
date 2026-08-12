---
title: Table
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्लाइड पर एक तालिका को दर्शाता है।
type: docs
weight: 5409
url: /hi/aspose.slides/table/
---
## Table क्लास


Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक का उपयोग कर वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | सिर्फ़ आंतरिक उपयोग के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक आकार से सम्बंधित वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक आकार से सम्बंधित वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर कॉलम लौटाता है। केवल-पढ़ने योग्य [Aspose::Slides::IColumn](../icolumn/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | कॉलमों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IColumnCollection](../icolumncollection/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकार पर लागू पिक्सेल इफ़ेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | [Table](./) के लिए फाइल फॉर्मेटिंग वाले [TableFormat::get_FillFormat](../tableformat/get_fillformat/) ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| **bool** [get_FirstCol](./get_firstcol/)() override | निर्धारित करता है कि तालिका की पहली कॉलम को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| **bool** [get_FirstRow](./get_firstrow/)() override | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | आकार की लॉकिंग सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई पॉइंट्स में मापता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें **bool**। |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | निर्धारित करता है कि सम पंक्तियों को अलग फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_LastCol](./get_lastcol/)() override | निर्धारित करता है कि तालिका की अंतिम कॉलम को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| **bool** [get_LastRow](./get_lastrow/)() override | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकार के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ वाले [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकार का नाम लौटाता है। इसे null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का प्रयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | **uint32_t** एक स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो आकार के जीवनकाल भर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | एक आकार के प्लेसहोल्डर को लौटाता है। यदि आकार के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रेजेंटेशन को लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | रॉ आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | निर्धारित करता है कि तालिका का पढ़ने क्रम दाएँ से बाएँ है या नहीं। पढ़ें **bool**। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमा‍ने के डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर पंक्ति लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | पंक्तियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IRowCollection](../irowcollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार की लॉकिंग सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | एक आकार की पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | बिल्ट-इन टेबल स्टाइल प्राप्त करता है। पढ़ें [TableStylePreset](../tablestylepreset/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | इस टेबल के लिए फॉर्मेटिंग प्रॉपर्टीज़ वाला [TableFormat](../tableformat/) ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITableFormat](../itableformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | एक आकार के 3D प्रभाव प्रॉपर्टीज़ वाला [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | **uint32_t** एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | निर्धारित करता है कि सम कॉलमों को अलग फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई पॉइंट्स में मापता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी-बाएँ कोणे का x-निर्देशांक पॉइंट्स में मापता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी-बाएँ कोणे का y-निर्देशांक पॉइंट्स में मापता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | **int32_t** आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले आकार को लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ा रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स प्रकार का उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार का थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए कंटेंट से गणना किए गए आकार की विज़ुअल बाउंड्स प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | निर्दिष्ट कॉलम और पंक्ति इंडेक्स पर सेल लौटाता है। केवल-पढ़ने योग्य [Cell](../cell/)। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉकिंग के रूप में लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | पड़ोसी सेल्स को मर्ज करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस को nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकार से सम्बंधित वैकल्पिक टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकार से सम्बंधित वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | निर्धारित करता है कि तालिका की पहली कॉलम को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | निर्धारित करता है कि सम पंक्तियों को अलग फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_LastCol](./set_lastcol/)(**bool**) override | निर्धारित करता है कि तालिका की अंतिम कॉलम को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_LastRow](./set_lastrow/)(**bool**) override | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग वैल्यू उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | रॉ आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | निर्धारित करता है कि तालिका का पढ़ने क्रम दाएँ से बाएँ है या नहीं। लिखता है **bool**। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमा‍ने के डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। लिखें **float**। |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | बिल्ट-इन टेबल स्टाइल सेट करता है। लिखें [TableStylePreset](../tablestylepreset/)। |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | निर्धारित करता है कि सम कॉलमों को अलग फॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं। लिखें **bool**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोणे का x-निर्देशांक पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोणे का y-निर्देशांक पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की सुविधा देता है। |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | सभी टेबल सेल्स के भागों पर परिभाषित पोर्शन फॉर्मेट प्रॉपर्टीज़ सेट करता है। |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | सभी टेबल सेल्स के पैराग्राफ़ पर परिभाषित पैराग्राफ़ फॉर्मेट प्रॉपर्टीज़ सेट करता है। |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | सभी टेबल सेल्स के टेक्स्ट फ्रेम पर परिभाषित टेक्स्ट फ्रेम फॉर्मेट प्रॉपर्टीज़ सेट करता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉकिंग के रूप में लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## संबंधित देखें

* Class [GraphicalObject](../graphicalobject/)
* Class [ITable](../itable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)