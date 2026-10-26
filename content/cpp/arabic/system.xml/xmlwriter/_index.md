---
title: XmlWriter
second_title: مرجع API Aspose.Slides للـ C++
description: يمثل كاتبًا يوفر طريقة سريعة غير مخزَّنة مؤقتًا وتعمل في اتجاه واحد لتوليد تدفقات أو ملفات تحتوي على بيانات XML.
type: docs
weight: 573
url: /ar/system.xml/xmlwriter/
---
## XmlWriter فئة


Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Close](./close/)() | عند تجاوزها في فئة مشتقة، تُغلق هذا الدفق والدفق الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام اسم الملف المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام اسم الملف و كائن [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام الدفق المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام الدفق وكائن [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام الـ TextWriter المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام الـ TextWriter وكائنات [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام الـ [Text::StringBuilder](../../system.text/stringbuilder/) المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام كائنات [Text::StringBuilder](../../system.text/stringbuilder/) و [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام كائن [XmlWriter](./) المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ مثيلاً جديداً من [XmlWriter](./) باستخدام كائنات [XmlWriter](./) و [XmlWriterSettings](../xmlwritersettings/) المحددة. |
| void [Dispose](./dispose/)() override | يفرج جميع الموارد المستخدمة بواسطة المثيل الحالي من فئة [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام semantics [Object.Equals](../../system/object/equals/) للـ C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual void [Flush](./flush/)() | عند تجاوزها في فئة مشتقة، تُفرغ كل ما هو في الذاكرة المؤقتة إلى الدفقات الأساسية وتفرغ أيضاً الدفق الأساسي. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | يرجع كائن [XmlWriterSettings](../xmlwritersettings/) المستخدم لإنشاء هذا المثيل [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | عند تجاوزها في فئة مشتقة، يحصل على حالة الكاتب. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | عند تجاوزها في فئة مشتقة، يحصل على نطاق **xml:lang** الحالي. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | عند تجاوزها في فئة مشتقة، يحصل على XmlSpace الذي يمثل نطاق **xml:space** الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، تُعيد أقرب بادئة معرفة في نطاق المجال الحالي لعنوان URI الخاص بالمجال. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئاً فعلياً، فقط يهيئ كائناً جديداً ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئاً فعلياً، فقط يهيئ كائناً جديداً ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط قالب الـ n'th ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | عند تجاوزها في فئة مشتقة، تكتب جميع الصفات الموجودة في الموضع الحالي في [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب صفةً بالاسم المحلي المحدد، وعنوان URI للمجال، والقيمة. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تكتب الصفة بالاسم المحلي والقيمة المحددين. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تكتب الصفة بالبادئة، الاسم المحلي، عنوان URI للمجال، والقيمة المحددة. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يشفر البايتات الثنائية المحددة كـ Base64 ويكتب النص الناتج. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يشفر البايتات الثنائية المحددة كـ **BinHex** ويكتب النص الناتج. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | يكتب كتلة **...** تحتوي على النص المحدد. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | يفرض توليد كيان حرف لقيمة Unicode المحددة. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يكتب النص مخزنًا مؤقتًا واحدًا في كل مرة. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | يكتب تعليق **** يحتوي على النص المحدد. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب إعلان DOCTYPE بالاسم المحدد والصفات الاختيارية. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصراً بالاسم المحلي والقيمة المحددين. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصراً بالاسم المحلي، عنوان URI للمجال، والقيمة المحددين. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصراً بالبادئة، الاسم المحلي، عنوان URI للمجال، والقيمة المحددين. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | عند تجاوزها في فئة مشتقة، تغلق الاستدعاء السابق XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | عند تجاوزها في فئة مشتقة، تغلق أي عناصر أو صفات مفتوحة وتعيد الكاتب إلى حالة البداية. |
| virtual void [WriteEndElement](./writeendelement/)() | عند تجاوزها في فئة مشتقة، تغلق عنصرًا واحدًا وتزيل نطاق المجال المقابل من المكدس. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب إشارة كيان كـ **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | عند تجاوزها في فئة مشتقة، تغلق عنصرًا واحدًا وتزيل نطاق المجال المقابل من المكدس. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب الاسم المحدد، مع التأكد من كونه اسماً صالحاً وفقاً لتوصية W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب الاسم المحدد، مع التأكد من كونه NmToken صالحاً وفقاً لتوصية W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | عند تجاوزها في فئة مشتقة، تنسخ كل شيء من القارئ إلى الكاتب وتنتقل بالقارئ إلى بداية الأخ الأصغر التالي. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | ينسخ كل شيء من كائن XPathNavigator إلى الكاتب. يبقى موقع XPathNavigator دون تغيير. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، تكتب تعليمًا للمعالجة مع مسافة بين الاسم والنص كما يلي: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب الاسم المؤهل بالمجال. تبحث هذه الطريقة عن البادئة المتاحة للنطاق المحدد. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | عند تجاوزها في فئة مشتقة، تكتب العلامات الخام يدوياً من مخزن الأحرف. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، تكتب العلامات الخام يدوياً من سلسلة. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب بداية صفة بالاسم المحلي وعنوان URI للمجال المحددين. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب بداية صفة بالبادئة، الاسم المحلي، وعنوان URI للمجال المحددين. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | يكتب بداية صفة بالاسم المحلي المحدد. |
| virtual void [WriteStartDocument](./writestartdocument/)() | عند تجاوزها في فئة مشتقة، يكتب إعلان XML بالإصدار "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | عند تجاوزها في فئة مشتقة، يكتب إعلان XML بالإصدار "1.0" والخاصية standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب العلامة البادئة المحددة ويربطها بالمجال المعطى. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب العلامة البادئة المحددة ويربطها بالمجال والبادئة المعطاة. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب علامة بدء بالاسم المحلي المحدد. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب محتوى النص المعطى. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | عند تجاوزها في فئة مشتقة، يولد ويكتب كيان الحرف البديل للزوج البديل من الأحرف. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يكتب قيمة الكائن. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | يكتب قيمة [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | يكتب قيمة [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | يكتب قيمة [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | يكتب قيمة [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | يكتب قيمة [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | يكتب عددًا ذا نقطة عائمة ذات دقة مفردة. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | يكتب قيمة [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | يكتب قيمة [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | يكتب قيمة [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يكتب المسافة البيضاء المعطاة. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## تعريفات النوع

| تعريف النوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اختصار لمؤشر مشترك إلى مثيل من هذه الفئة. |

## انظر أيضاً

* فئة [IDisposable](../../system/idisposable/)
* مساحة الاسم [System::Xml](../)
* مكتبة [Aspose.Slides](../../)