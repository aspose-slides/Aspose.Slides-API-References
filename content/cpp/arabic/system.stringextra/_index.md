---
title: "System::StringExtra"
second_title: "Aspose.Slides للـ C++ مرجع API"
description: 
type: docs
weight: 911
url: /ar/system.stringextra/
---
## الدوال

| الدالة | الوصف |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | يقوم بدمج مصفوفة السلاسل. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | يقوم بدمج السلاسل. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | يقوم بدمج السلاسل. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | يقوم بدمج السلاسل. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | يحول عدة كائنات إلى سلاسل ويقوم بدمج السلاسل الناتجة. تخصيص لأنواع [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | يحول عدة كائنات إلى سلاسل ويقوم بدمج السلاسل الناتجة. تخصيص للأنواع العددية. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | يحول عدة كائنات إلى سلاسل ويقوم بدمج السلاسل الناتجة. تخصيص للتركيبات وأنواع القيم الأخرى. |