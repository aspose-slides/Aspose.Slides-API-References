---
title: "System::StringExtra"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 911
url: /zh-hant/system.stringextra/
---
## 函式

| 函式 | 描述 |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | 串接字串陣列。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | 串接字串。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 串接字串。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 串接字串。 |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 將多個物件轉換為字串並串接結果字串。針對 [SmartPtr](../system/smartptr/) 型別的特化。 |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 將多個物件轉換為字串並串接結果字串。針對算術型別的特化。 |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 將多個物件轉換為字串並串接結果字串。針對結構和其他值型別的特化。 |