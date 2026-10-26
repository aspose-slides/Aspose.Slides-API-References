---
title: BinaryReader
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل قارئًا يقرأ الأنواع الأولية من البيانات كبيانات ثنائية بترميز معين. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 92
url: /ar/system.io/binaryreader/
---
## BinaryReader فئة


يمثل قارئًا يقرأ الأنواع الأولية من البيانات كبيانات ثنائية بترميز معين. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class BinaryReader : public System::IDisposable
```

## الطرق

| Method | Description |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينشئ نسخة من الفئة [BinaryReader](./) التي تقرأ البيانات من التدفق المحدد باستخدام ترميز UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | ينشئ نسخة من الفئة [BinaryReader](./) التي تقرأ البيانات من التدفق المحدد باستخدام الترميز المحدد. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | ينشئ نسخة من الفئة [BinaryReader](./) التي تقرأ البيانات من التدفق المحدد باستخدام الترميز المحدد. |
| virtual void [Close](./close/)() | يغلق كائن [BinaryReader](./) الحالي وتدفق الإدخال الأساسي. |
| void [Dispose](./dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق التدفق الأساسي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانين متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة مزدوجة الدقة على نمط C# حيث يُعتبر NaNانين متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | يرجع تدفق الإدخال. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مكافئ طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مكافئ لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). يُستدعى مباشرة أو باستخدام كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مكافئ طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويمكّن بناء النسخ للصفوف الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويمكّن بناء النسخ للصفوف الفرعية. |
| virtual int [PeekChar](./peekchar/)() | يقرأ حرفًا واحدًا من تدفق الإدخال دون تعديل موضع القراءة في التدفق. |
| virtual int [Read](./read/)() | يقرأ حرفًا واحدًا من تدفق الإدخال. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يقرا عدد البايتات المحدد من تدفق الإدخال ويكتبها إلى مصفوفة البايتات المحددة. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يقرا عدد الأحرف المحدد من تدفق الإدخال، يحولها إلى ترميز UTF-16 ويكتب الأحرف الناتجة إلى مصفوفة الأحرف المحددة بدءًا من الموضع المحدد. |
| virtual **bool** [ReadBoolean](./readboolean/)() | يقرأ بايتًا واحدًا من تدفق الإدخال ويعيد تمثيله المنطقي. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | يقرأ بايتًا واحدًا من تدفق الإدخال. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | يقرا عدد البايتات المحدد من تدفق الإدخال. |
| virtual char_t [ReadChar](./readchar/)() | يقرأ حرفًا واحدًا من تدفق الإدخال. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | يقرا عدد الأحرف المحدد من تدفق الإدخال ويعيدها بترميز UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | غير مُنفذ. |
| virtual **double** [ReadDouble](./readdouble/)() | يقرأ 8 بايتات من تدفق الإدخال ويعيدها كقيمة مزدوجة الدقة. |
| virtual **int16_t** [ReadInt16](./readint16/)() | يقرأ 2 بايت من تدفق الإدخال ويعيدها كقيمة عدد صحيح 16 بت. |
| virtual int [ReadInt32](./readint32/)() | يقرأ 4 بايتات من تدفق الإدخال ويعيدها كقيمة عدد صحيح 32 بت. |
| virtual **int64_t** [ReadInt64](./readint64/)() | يقرأ 8 بايتات من تدفق الإدخال ويعيدها كقيمة عدد صحيح 64 بت. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | يقرأ بايتًا واحدًا من تدفق الإدخال ويعيده كقيمة عدد صحيح موقّع 8 بت. |
| virtual **float** [ReadSingle](./readsingle/)() | يقرأ 4 بايتات من تدفق الإدخال ويعيدها كقيمة عدد عائم بدقة مفردة. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | يقرأ سلسلة من التدفق الحالي. السلسلة مسبوقة بالطول، المشفر كعدد صحيح بسبعة بتات في كل مرة. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | يقرأ 2 بايت من تدفق الإدخال ويعيدها كقيمة عدد صحيح غير موقّع 16 بت. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | يقرأ 4 بايتات من تدفق الإدخال ويعيدها كقيمة عدد صحيح غير موقّع 32 بت. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | يقرأ 8 بايتات من تدفق الإدخال ويعيدها كقيمة عدد صحيح غير موقّع 64 بت. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | yضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مكافئ طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). يُستدعى مباشرة أو باستخدام كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضاً

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)