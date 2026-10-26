---
title: "System::Xml::Schema"
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: 
type: docs
weight: 1145
url: /ar/system.xml.schema/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Details_XmlSchemaException](./details_xmlschemaexception/) | يرجع معلومات مفصلة حول استثناء المخطط. |
| [Details_XmlSchemaInferenceException](./details_xmlschemainferenceexception/) | يرجع معلومات حول الأخطاء التي واجهتها الفئة [XmlSchemaInference](./xmlschemainference/) أثناء استنتاج مخطط من مستند XML. |
| [Details_XmlSchemaValidationException](./details_xmlschemavalidationexception/) | يمثل الاستثناء الذي يُرمى عندما يتم مواجهة أخطاء وتحذيرات التحقق من مخطط XML [Schema](./) Definition Language (XSD) في مستند XML يتم التحقق منه. |
| [IXmlSchemaInfo](./ixmlschemainfo/) | يحدد معلومات ما بعد تحقق المخطط (infoset) لعقدة XML تم التحقق منها. |
| [ValidationEventArgs](./validationeventargs/) | يرجع معلومات مفصلة متعلقة بـ ValidationEventHandler. |
| [XmlAtomicValue](./xmlatomicvalue/) | يمثل القيمة المكتوبة لعنصر XML أو سمة تم التحقق منها. لا يمكن فئة [XmlAtomicValue](./xmlatomicvalue/) أن تُورث. |
| [XmlSchema](./xmlschema/) | تمثيل في الذاكرة لـ XML [Schema](./)، كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) و[XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/). |
| [XmlSchemaAll](./xmlschemaall/) | يمثل عنصر **all** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaAnnotated](./xmlschemaannotated/) | الفئة الأساسية لأي عنصر يمكنه احتواء عناصر التعليق. |
| [XmlSchemaAnnotation](./xmlschemaannotation/) | يمثل عنصر **annotation** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaAny](./xmlschemaany/) | يمثل عنصر **any** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaAnyAttribute](./xmlschemaanyattribute/) | يمثل عنصر **anyAttribute** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaAppInfo](./xmlschemaappinfo/) | يمثل عنصر **appinfo** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaAttribute](./xmlschemaattribute/) | يمثل عنصر **attribute** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). توفر السمات معلومات إضافية لعناصر المستند الأخرى. يتم تضمين وسم السمة بين وسوم عنصر المستند للمخطط. يعرض مستند XML السمات كعناصر مسماة في وسم الفتح للعنصر. |
| [XmlSchemaAttributeGroup](./xmlschemaattributegroup/) | يمثل عنصر **attributeGroup** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). توفر مجموعات السمات (AttributesGroups) آلية لتجميع مجموعة من إعلانات السمات بحيث يمكن دمجها كمجموعة داخل تعريفات الأنواع المركبة. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/) | يمثل عنصر **attributeGroup** مع سمة **ref** من XML [Schema](./) كما هو محدد في [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454). يمثل AttributesGroupRef المرجع لمجموعة السمات، وتحتوي خاصية الاسم على مجموعة السمات المرجعية. |
| [XmlSchemaChoice](./xmlschemachoice/) | يمثل عنصر **choice** (مُركب) من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يسمح **choice** بوجود أحد أبنائه فقط في نسخة. |
| [XmlSchemaCollection](./xmlschemacollection/) | يحتوي على ذاكرة مخبئية لمخططات XML [Schema](./) definition language (XSD) وXML-Data Reduced (XDR). |
| [XmlSchemaCollectionEnumerator](./xmlschemacollectionenumerator/) | يدعم تكرارًا بسيطًا على مجموعة. لا يمكن وراثة هذه الفئة. |
| [XmlSchemaCompilationSettings](./xmlschemacompilationsettings/) | يوفر خيارات تجميع المخطط لفئة [XmlSchemaSet](./xmlschemaset/). لا يمكن وراثة هذه الفئة. |
| [XmlSchemaComplexContent](./xmlschemacomplexcontent/) | يمثل عنصر **complexContent** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تمثل هذه الفئة نموذج المحتوى المعقد للأنواع المركبة. يحتوي على امتدادات أو قيود على نوع معقد يملك إما عناصر فقط أو محتوى مختلط. |
| [XmlSchemaComplexContentExtension](./xmlschemacomplexcontentextension/) | يمثل عنصر **extension** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة مخصصة للأنواع المركبة ذات نموذج محتوى معقد مستمد عن طريق الامتداد. تقوم بتمديد النوع المعقد بإضافة سمات أو عناصر. |
| [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/) | يمثل عنصر **restriction** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة مخصصة للأنواع المركبة ذات نموذج محتوى معقد مستدم عن طريق القيد. تقيد محتويات النوع المعقد إلى مجموعة فرعية من النوع المعقد الموروث. |
| [XmlSchemaComplexType](./xmlschemacomplextype/) | يمثل عنصر **complexType** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة تعرف نوعًا مركبًا يحدد مجموعة السمات ومحتوى العنصر. |
| [XmlSchemaContent](./xmlschemacontent/) | فئة تجريدية لمحتوى المخطط. |
| [XmlSchemaContentModel](./xmlschemacontentmodel/) | يحدد ترتيب وبنية العناصر الفرعية لنوع. |
| [XmlSchemaDatatype](./xmlschemadatatype/) | فئة [XmlSchemaDatatype](./xmlschemadatatype/) هي فئة تجريدية لتعيين أنواع XML [Schema](./) definition language (XSD) إلى أنواع وقت التنفيذ. |
| [XmlSchemaDocumentation](./xmlschemadocumentation/) | يمثل عنصر **documentation** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُحدد هذه الفئة المعلومات التي يقرؤها أو يستخدمها البشر داخل **annotation**. |
| [XmlSchemaElement](./xmlschemaelement/) | يمثل عنصر **element** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة هي الفئة الأساسية لجميع أنواع الجسيمات وتُستخدم لوصف عنصر في مستند XML. |
| [XmlSchemaEnumerationFacet](./xmlschemaenumerationfacet/) | يمثل جانب **enumeration** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُحدد هذه الفئة قائمة بالقيم الصالحة لعنصر simpleType. يُضمّن الإعلان داخل إعلان **restriction**. |
| [XmlSchemaExternal](./xmlschemaexternal/) | يوفر معلومات حول المخطط المشمول. |
| [XmlSchemaFacet](./xmlschemafacet/) | فئة أساسية لجميع الجوانب المستخدمة عندما تُشتق الأنواع البسيطة عن طريق القيد. |
| [XmlSchemaFractionDigitsFacet](./xmlschemafractiondigitsfacet/) | يحدد قيدًا على عدد الأرقام التي يمكن إدخالها لقيمة الجزء العشري لعنصر simpleType. يجب أن تكون قيمة fractionDigits عددًا صحيحًا موجبًا. يمثل جانب **fractionDigits** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaGroup](./xmlschemagroup/) | يمثل عنصر **group** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُعرّف هذه الفئة مجموعات على مستوى **schema** يتم الإشارة إليها من الأنواع المركبة. تقوم بتجميع مجموعة من إعلانات العناصر بحيث يمكن دمجها كمجموعة داخل تعريفات الأنواع المركبة. |
| [XmlSchemaGroupBase](./xmlschemagroupbase/) | فئة تجريدية لـ [XmlSchemaAll](./xmlschemaall/)، [XmlSchemaChoice](./xmlschemachoice/)، أو [XmlSchemaSequence](./xmlschemasequence/). |
| [XmlSchemaGroupRef](./xmlschemagroupref/) | يمثل عنصر **group** مع سمة **ref** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُستخدم هذه الفئة داخل الأنواع المركبة التي تشير إلى **group** معرّف على مستوى **schema**. |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/) | فئة لقيود الهوية: عناصر **key**، **keyref**، و**unique**. |
| [XmlSchemaImport](./xmlschemaimport/) | يمثل عنصر **import** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُستخدم هذه الفئة لاستيراد مكوّنات المخطط من مخططات أخرى. |
| [XmlSchemaInclude](./xmlschemainclude/) | يمثل عنصر **include** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). تُستخدم هذه الفئة لتضمين إعلانات وتعريفات من مخطط خارجي. تُصبح الإعلانات والتعريفات المضمّنة متاحة بعد ذلك للمعالجة في المخطط الحاوي. |
| [XmlSchemaInference](./xmlschemainference/) | يستنتج مخطط XML [Schema](./) Definition Language (XSD) من مستند XML. لا يمكن وراثة الفئة [XmlSchemaInference](./xmlschemainference/). |
| [XmlSchemaInfo](./xmlschemainfo/) | يمثل معلومات ما بعد تحقق المخطط (infoset) لعقدة XML تم التحقق منها. |
| [XmlSchemaKey](./xmlschemakey/) | تمثل هذه الفئة عنصر **key** من XMLSchema كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaKeyref](./xmlschemakeyref/) | تمثل هذه الفئة عنصر **keyref** من XMLSchema كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaLengthFacet](./xmlschemalengthfacet/) | يمثل جانب **length** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على طول عنصر **simpleType** على نوع البيانات. |
| [XmlSchemaMaxExclusiveFacet](./xmlschemamaxexclusivefacet/) | يمثل عنصر **maxExclusive** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على القيمة القصوى لعنصر **simpleType**. يجب أن تكون قيمة العنصر أقل من قيمة عنصر **maxExclusive**. |
| [XmlSchemaMaxInclusiveFacet](./xmlschemamaxinclusivefacet/) | يمثل عنصر **maxInclusive** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على القيمة القصوى لعنصر **simpleType**. يجب أن تكون قيمة العنصر أقل من أو مساوية لقيمة عنصر **maxInclusive**. |
| [XmlSchemaMaxLengthFacet](./xmlschemamaxlengthfacet/) | يمثل عنصر **maxLength** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على الحد الأقصى لطول قيمة البيانات لعنصر **simpleType**. يجب أن يكون الطول أقل من قيمة عنصر **maxLength**. |
| [XmlSchemaMinExclusiveFacet](./xmlschemaminexclusivefacet/) | يمثل عنصر **minExclusive** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على الحد الأدنى لقيمة عنصر **simpleType**. يجب أن تكون قيمة العنصر أكبر من قيمة عنصر **minExclusive**. |
| [XmlSchemaMinInclusiveFacet](./xmlschemamininclusivefacet/) | يمثل عنصر **minInclusive** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على الحد الأدنى لقيمة عنصر simpleType. يجب أن تكون قيمة العنصر أكبر من أو مساوية لقيمة عنصر **minInclusive**. |
| [XmlSchemaMinLengthFacet](./xmlschemaminlengthfacet/) | يمثل عنصر **minLength** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على الحد الأدنى لطول قيمة البيانات لعنصر **simpleType**. يجب أن يكون الطول أكبر من قيمة عنصر **minLength**. |
| [XmlSchemaNotation](./xmlschemanotation/) | يمثل عنصر **notation** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). إعلان **notation** في XML [Schema](./) هو إعادة بناء لإعلانات NOTATION في XML 1.0. هدف النوتات هو وصف تنسيق البيانات غير XML داخل مستند XML. |
| [XmlSchemaNumericFacet](./xmlschemanumericfacet/) | فئة أساسية لتعريف الجوانب **numeric**. هذه الفئة هي الفئة الأساسية لفئات الجوانب العددية مثل [XmlSchemaMinLengthFacet](./xmlschemaminlengthfacet/). |
| [XmlSchemaObject](./xmlschemaobject/) | يمثل الفئة الجذرية لهرم نموذج كائن المخطط [Xml](../system.xml/) ويعمل كفئة أساسية لفئات مثل الفئة [XmlSchema](./xmlschema/). |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/) | مجموعة من XmlSchemaObjects. |
| [XmlSchemaObjectEnumerator](./xmlschemaobjectenumerator/) | يمثل المُعدد لـ [XmlSchemaObjectCollection](./xmlschemaobjectcollection/). |
| [XmlSchemaObjectTable](./xmlschemaobjecttable/) | يوفر المجموعات للعناصر المحتواة في الفئة [XmlSchema](./xmlschema/) (مثل Attributes، AttributeGroups، Elements، وغيرها). |
| [XmlSchemaParticle](./xmlschemaparticle/) | فئة أساسية هي الفئة الأساسية لجميع أنواع الجسيمات (مثل [XmlSchemaAny](./xmlschemaany/)). |
| [XmlSchemaPatternFacet](./xmlschemapatternfacet/) | يمثل عنصر **pattern** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على القيمة المدخلة لعنصر **simpleType**. |
| [XmlSchemaRedefine](./xmlschemaredefine/) | يمثل عنصر **redefine** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة للسماح بإعادة تعريف الأنواع البسيطة والمعقدة والمجموعات ومجموعات السمات من ملفات مخطط خارجية في المخطط الحالي. يمكن أيضًا استخدامها لتوفير إصدارات لعناصر المخطط. |
| [XmlSchemaSequence](./xmlschemasequence/) | يمثل عنصر **sequence** (مُركب) من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يتطلب **sequence** ظهور العناصر في المجموعة بالترتيب المحدد داخل العنصر الحاوي. |
| [XmlSchemaSet](./xmlschemaset/) | يحتوي على ذاكرة مخبئية لمخططات XML [Schema](./) definition language (XSD). |
| [XmlSchemaSimpleContent](./xmlschemasimplecontent/) | يمثل عنصر **simpleContent** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة مخصصة للأنواع البسيطة والمعقدة ذات نموذج محتوى بسيط. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/) | يمثل عنصر **extension** للمحتوى البسيط من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لاشتقاق الأنواع البسيطة عن طريق الامتداد. تُستخدم هذه الاشتقاقات لتوسيع محتوى النوع البسيط للعنصر بإضافة سمات. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/) | يمثل عنصر **restriction** للمحتوى البسيط من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لاشتقاق الأنواع البسيطة عن طريق القيد. يمكن استخدام هذه الاشتقاقات لتقييد نطاق القيم للعنصر إلى مجموعة فرعية من القيم المحددة في النوع البسيط الموروث. |
| [XmlSchemaSimpleType](./xmlschemasimpletype/) | يمثل عنصر **simpleType** للمحتوى البسيط من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). هذه الفئة تعرف نوعًا بسيطًا. يمكن للأنواع البسيطة تحديد المعلومات والقيود لقيمة السمات أو العناصر ذات المحتوى النصي فقط. |
| [XmlSchemaSimpleTypeContent](./xmlschemasimpletypecontent/) | فئة أساسية لفئات محتوى النوع البسيط. |
| [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/) | يمثل عنصر **list** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتعريف عنصر **simpleType** كقائمة من القيم لنوع بيانات محدد. |
| [XmlSchemaSimpleTypeRestriction](./xmlschemasimpletyperestriction/) | يمثل عنصر **restriction** للأنواع البسيطة من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتقييد عنصر **simpleType**. |
| [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/) | يمثل عنصر **union** للأنواع البسيطة من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام نوع بيانات **union** لتحديد محتوى **simpleType**. يجب أن تكون قيمة عنصر **simpleType** إحدى مجموعة من أنواع البيانات البديلة المحددة في الاتحاد. تكون أنواع الاتحاد دائمًا أنواعًا مشتقة ويجب أن تشمل على الأقل نوعي بيانات بديلين. |
| [XmlSchemaTotalDigitsFacet](./xmlschematotaldigitsfacet/) | يمثل جانب **totalDigits** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد على عدد الأرقام التي يمكن إدخالها لقيمة عنصر **simpleType**. يجب أن تكون قيمة **totalDigits** عددًا صحيحًا موجبًا. |
| [XmlSchemaType](./xmlschematype/) | الفئة الأساسية لجميع الأنواع البسيطة والمعقدة. |
| [XmlSchemaUnique](./xmlschemaunique/) | يمثل عنصر **unique** من XML [Schema](./) كما هو محدد في World Wide [Web](../system.web/) Consortium (W3C). يمكن استخدام هذه الفئة لتحديد قيد فريد بين مجموعة من العناصر. |
| [XmlSchemaValidator](./xmlschemavalidator/) | يمثل محرك التحقق من XML [Schema](./) Definition Language (XSD) [Schema](./). لا يمكن وراثة الفئة [XmlSchemaValidator](./xmlschemavalidator/). |
| [XmlSchemaWhiteSpaceFacet](./xmlschemawhitespacefacet/) | يمثل جانب **whiteSpace** من World Wide [Web](../system.web/) Consortium (W3C). |
| [XmlSchemaXPath](./xmlschemaxpath/) | يمثل عنصر **selector** من World Wide [Web](../system.web/) Consortium (W3C). |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [XmlSchemaContentProcessing](./xmlschemacontentprocessing/) | يوفر معلومات حول وضع التحقق من استبدالات العنصر **any** و**anyAttribute**. |
| [XmlSchemaContentType](./xmlschemacontenttype/) | تعدادات لنموذج محتوى النوع المركب. يمثل هذا المحتوى في مجموعة معلومات ما بعد تحقق المخطط (infoset). |
| [XmlSchemaDatatypeVariety](./xmlschemadatatypevariety/) | يحدد تنوع نوع بيانات مخطط XML W3C لهذا النوع. |
| [XmlSchemaDerivationMethod](./xmlschemaderivationmethod/) | يوفر طرقًا مختلفة لمنع الاشتقاق. |
| [XmlSchemaForm](./xmlschemaform/) | يشير إلى ما إذا كان يجب تأهيل السمات أو العناصر ببادئة مساحة الاسم. |
| [XmlSchemaUse](./xmlschemause/) | مؤشر لكيفية استخدام السمة. |
| [XmlSchemaValidationFlags](./xmlschemavalidationflags/) | يحدد خيارات التحقق من المخطط المستخدمة بواسطة الفئات [XmlSchemaValidator](./xmlschemavalidator/) و[XmlReader](../system.xml/xmlreader/). |
| [XmlSchemaValidity](./xmlschemavalidity/) | يمثل صِحة عنصر XML تم التحقق منه بواسطة الفئة [XmlSchemaValidator](./xmlschemavalidator/). |
| [XmlSeverityType](./xmlseveritytype/) | يمثل شدة حدث التحقق. |
| [XmlTypeCode](./xmltypecode/) | يمثل أنواع مخطط XML [Schema](./) Definition Language (XSD) الخاصة بـ W3C. |

## Typedefs

| نوع التعريف | الوصف |
| --- | --- |
| [XmlSchemaInferenceException](./xmlschemainferenceexception/) |  |
| [ValidationEventHandler](./validationeventhandler/) | يمثل طريقة الاستدعاء التي ستتعامل مع أحداث التحقق من مخطط XML و[ValidationEventArgs](./validationeventargs/). |
| [XmlSchemaException](./xmlschemaexception/) |  |
| [XmlSchemaValidationException](./xmlschemavalidationexception/) |  |
| [XmlValueGetter](./xmlvaluegetter/) | استدعاء يتم استخدامه بواسطة الفئة [XmlSchemaValidator](./xmlschemavalidator/) لتمرير قيم السمة والنص والمسافات البيضاء كنوع وقت تشغيل متوافق مع نوع XML [Schema](./) Definition Language (XSD) للسمة أو النص أو المسافة البيضاء.