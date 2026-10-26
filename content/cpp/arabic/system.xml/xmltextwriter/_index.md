---
title: XmlTextWriter
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل كاتبًا يوفر طريقة سريعة غير مخزَّنة للأمام لتوليد تدفقات أو ملفات تحتوي على بيانات XML تتوافق مع لغة الترميز القابلة للامتداد (XML) 1.0 وتوصيات الأسماء في XML الصادرة عن W3C.
type: docs
weight: 521
url: /ar/system.xml/xmltextwriter/
---
## XmlTextWriter class

يمثل كاتبًا يوفر طريقة سريعة غير مخزَّنة للأمام لتوليد تدفقات أو ملفات تحتوي على بيانات XML تتوافق مع لغة الترميز القابلة للامتداد (XML) 1.0 وتوصيات الأسماء في XML الصادرة عن W3C.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| void [Close](./close/)() override | يغلق هذا التيار والتيار الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام اسم الملف المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام اسم الملف وكائن [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام التيار المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام التيار وكائن [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام الـ TextWriter المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام الـ TextWriter وكائنات [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام [Text::StringBuilder](../../system.text/stringbuilder/) المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام كائنات [Text::StringBuilder](../../system.text/stringbuilder/) و[XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام كائن [XmlWriter](../xmlwriter/) المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ينشئ كائنًا جديدًا من [XmlWriter](../xmlwriter/) باستخدام كائنات [XmlWriter](../xmlwriter/) و[XmlWriterSettings](../xmlwritersettings/) المحددة. |
| void [Dispose](../xmlwriter/dispose/)() override | يطلق جميع الموارد المستخدمة من قبل المثيل الحالي من الفئة [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | يفرغ كل ما في المخزن المؤقت إلى التيارات الأساسية ويفرغ التيار الأساسي أيضًا. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | يعيد كائن التيار الأساسي. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | يشير إلى كيفية تنسيق الإخراج. |
| **int32_t** [get_Indentation](./get_indentation/)() | يعيد عدد حروف المسافة التي تُكتب لكل مستوى في الهرم عندما يتم تعيين [XmlTextWriter::set_Formatting](./set_formatting/) إلى [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | يعيد الحرف المستخدم للمسافة عندما يتم تعيين [XmlTextWriter::set_Formatting](./set_formatting/) إلى [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | يعيد قيمة تشير إلى ما إذا كان سيتم دعم النطاقات. |
| char16_t [get_QuoteChar](./get_quotechar/)() | يعيد الحرف المستخدم لتحديد قيم الصفات. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | يعيد كائن [XmlWriterSettings](../xmlwritersettings/) المستخدم لإنشاء المثيل [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | يعيد حالة الكاتب. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | يعيد نطاق **xml:lang** الحالي. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | يعيد XmlSpace الذي يمثل نطاق **xml:space** الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | يعيد أقرب بادئة معرفة في نطاق النطاق الحالي لـ URI الخاص بالنطاق. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل إسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | يشير إلى كيفية تنسيق الإخراج. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | يضبط عدد حروف المسافة لكل مستوى في الهرم عندما يتم تعيين [XmlTextWriter::set_Formatting](./set_formatting/) إلى [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | يضبط الحرف المستخدم للمسافة عندما يتم تعيين [XmlTextWriter::set_Formatting](./set_formatting/) إلى [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان سيتم دعم النطاقات. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | يضبط الحرف المستخدم لتحديد قيم الصفات. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط العنصر النمطي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ التركيب C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | عند تجاوزها في فئة مشتقة، يكتب جميع الصفات الموجودة في الموضع الحالي في [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب صفة بالاسم المحلي، URI النطاق، والقيمة المحددة. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب الصفة بالاسم المحلي والقيمة المحددة. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب الصفة بالبادئة، الاسم المحلي، URI النطاق، والقيمة المحددة. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقوم بترميز البايتات الثنائية المحددة كـ base64 ويكتب النص الناتج. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقوم بترميز البايتات الثنائية المحددة كـ binhex ويكتب النص الناتج. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | يكتب كتلة **...** تحتوي على النص المحدد. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | يفرض توليد كيان حرف للقيمة الموحدة المحددة. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | يكتب النص بواحد كل مرة من المخزن المؤقت. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | يكتب تعليقًا **** يحتوي على النص المحدد. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | يكتب إعلان DOCTYPE بالاسم المحدد والسمات الاختيارية. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصرًا بالاسم المحلي والقيمة المحددة. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصرًا بالاسم المحلي، URI النطاق، والقيمة المحددة. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب عنصرًا بالبادئة، الاسم المحلي، URI النطاق، والقيمة المحددة. |
| void [WriteEndAttribute](./writeendattribute/)() override | يغلق استدعاء [XmlTextWriter::WriteStartAttribute](./writestartattribute/) السابق. |
| void [WriteEndDocument](./writeenddocument/)() override | يغلق أي عناصر أو صفات مفتوحة ويعيد الكاتب إلى حالة البدء. |
| void [WriteEndElement](./writeendelement/)() override | يغلق عنصرًا واحدًا ويزيل نطاق النطاق المقابل. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | يكتب إشارة كيان كـ **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | يغلق عنصرًا واحدًا ويزيل نطاق النطاق المقابل. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | يكتب الاسم المحدد، ويتأكد من أنه اسم صالح وفقًا لـ [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | يكتب الاسم المحدد، ويتأكد من أنه **NmToken** صالح وفقًا لـ [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | عند تجاوزها في فئة مشتقة، ينسخ كل شيء من القارئ إلى الكاتب وينقل القارئ إلى بداية الأخ الأصغر التالي. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | ينسخ كل شيء من كائن XPathNavigator إلى الكاتب. يبقى موضع XPathNavigator دون تغيير. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | يكتب تعليمًا معالجة مع مسافة بين الاسم والنص كما يلي: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | يكتب الاسم المؤهل بالنطاق. تبحث هذه الطريقة عن البادئة الموجودة في النطاق المعطى. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | يكتب العلامة الخام يدويًا من مخزن محارف. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | يكتب العلامة الخام يدويًا من سلسلة. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | يكتب بدء صفة. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب بدء صفة بالاسم المحلي وURI النطاق المحدد. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | يكتب بدء صفة بالاسم المحلي المحدد. |
| void [WriteStartDocument](./writestartdocument/)() override | يكتب إعلان XML بالإصدار "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | يكتب إعلان XML بالإصدار "1.0" والخاصية standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | يكتب وسم البداية المحدد ويربطه بالنطاق والبادئة المعطاة. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب وسم البداية المحدد ويربطه بالنطاق المعطى. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يكتب وسم بداية بالاسم المحلي المحدد. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | يكتب محتوى النص المعطى. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | ينشئ ويكتب كيان الحرف البديل للزوج البديل. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يكتب قيمة الكائن. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | يكتب قيمة [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | يكتب قيمة [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | يكتب قيمة [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | يكتب قيمة [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | يكتب قيمة [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | يكتب عددًا عائمًا دقة مفردة. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | يكتب قيمة [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | يكتب قيمة [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | يكتب قيمة [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | يكتب المسافة البيضاء المعطاة. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | ينشئ مثيلًا من الفئة [XmlTextWriter](./) باستخدام التيار والترميز المحددين. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | ينشئ مثيلًا من الفئة [XmlTextWriter](./) باستخدام الملف المحدد. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ينشئ مثيلًا من الفئة [XmlTextWriter](./) باستخدام الـ TextWriter المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## Typedefs

| نوع تعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى مثيل من هذه الفئة. |

## ملاحظات

يوصى باستخدام الفئة [XmlWriter](../xmlwriter/) بدلاً من ذلك.

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبدًا مثيلات من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

## انظر أيضًا

* الفئة [XmlWriter](../xmlwriter/)
* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)