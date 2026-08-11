---
title: XmlSchemaDatatype
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: فئة XmlSchemaDatatype هي فئة مجردة لتعيين أنواع لغة تعريف مخطط XML (XSD) إلى أنواع وقت التشغيل.
type: docs
weight: 339
url: /ar/system.xml.schema/xmlschemadatatype/
---
## فئة XmlSchemaDatatype

الفئة [XmlSchemaDatatype](./) هي فئة مجردة لتعيين أنواع لغة تعريف XML [Schema](../) (XSD) إلى أنواع وقت التشغيل.

```cpp
class XmlSchemaDatatype : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | يقوم بتحويل القيمة المحددة، التي يكون نوعها أحد التمثيلات الصالحة لنوع مخطط XML الممثَّل بـ [XmlSchemaDatatype](./)، إلى نوع وقت التشغيل المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | يقوم بتحويل القيمة المحددة، التي يكون نوعها أحد التمثيلات الصالحة لنوع مخطط XML الممثَّل بـ [XmlSchemaDatatype](./)، إلى نوع وقت التشغيل المحدد باستخدام [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) إذا كان [XmlSchemaDatatype](./) يمثل النوع **xs:QName** أو نوعًا مشتقًا منه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام معنويات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث تُعتَبر قيمتا NaN مساوية رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة مزدوجة بأسلوب C# حيث تُعتَبر قيمتا NaN مساوية رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [XmlTokenizedType](../../system.xml/xmltokenizedtype/) [get_TokenizedType](./get_tokenizedtype/)() | عند تجاوزها في فئة مشتقة، يحصل على النوع لـ **string** كما هو موضح في مواصفة World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0. |
| virtual [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | يعيد قيمة XmlTypeCode للنوع البسيط. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | عند تجاوزها في فئة مشتقة، يحصل على نوع العنصر. |
| virtual [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) [get_Variety](./get_variety/)() | يعيد قيمة XmlSchemaDatatypeVariety للنوع البسيط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| virtual **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](./)\>) | هذه الطريقة تُعيد دائمًا **false**. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). نادِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ParseValue](./parsevalue/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | عند تجاوزها في فئة مشتقة، يتحقق من صحة **string** المحددة مقارنةً بنوع بسيط مدمج أو معرف من قبل المستخدم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقارنة مرجعية لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة string و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المعامل القالبي الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقَلّص ويُعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). نادِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقَلّص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى مثال من هذه الفئة. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)