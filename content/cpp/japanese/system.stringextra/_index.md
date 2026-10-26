---
title: "System::StringExtra"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 911
url: /ja/system.stringextra/
---
## 関数

| Function | Description |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | 文字列配列を連結します。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | 文字列を連結します。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 文字列を連結します。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 文字列を連結します。 |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 複数のオブジェクトを文字列に変換し、結果の文字列を連結します。[SmartPtr](../system/smartptr/) 型の特殊化です。 |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 複数のオブジェクトを文字列に変換し、結果の文字列を連結します。算術型の特殊化です。 |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 複数のオブジェクトを文字列に変換し、結果の文字列を連結します。構造体やその他の値型の特殊化です。 |