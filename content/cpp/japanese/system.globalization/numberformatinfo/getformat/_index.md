---
title: GetFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定のタイプのフォーマッタを取得します。
type: docs
weight: 742
url: /ja/system.globalization/numberformatinfo/getformat/
---
## NumberFormatInfo::GetFormat(const TypeInfo\&) メソッド

特定のタイプのフォーマッタを取得します。

```cpp
SharedPtr<Object> System::Globalization::NumberFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 取得するフォーマッタのタイプ；[NumberFormatInfo](../) タイプのみがサポートされています。 |

### 戻り値

フォーマッタ、または利用できない場合は null。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [NumberFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)