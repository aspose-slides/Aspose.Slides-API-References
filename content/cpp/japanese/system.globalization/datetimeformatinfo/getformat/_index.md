---
title: GetFormat()
second_title: Aspose.Slides の C++ API リファレンス
description: 特定のタイプのフォーマッタを取得します。
type: docs
weight: 14
url: /ja/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) メソッド

特定のタイプのフォーマッタを取得します。

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 取得するフォーマッタのタイプ; [DateTimeFormatInfo](../) タイプのみがサポートされます。 |

### 戻り値

フォーマッタ、または利用できない場合は null。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [DateTimeFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)