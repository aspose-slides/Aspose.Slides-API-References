---
title: XmlSchemaContentProcessing
second_title: C++ 用 Aspose.Slides API リファレンス
description: any および anyAttribute 要素の置換に対する検証モードに関する情報を提供します。
type: docs
weight: 976
url: /ja/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum


**any** と **anyAttribute** 要素の置換に対する検証モードに関する情報を提供します。

```cpp
enum class XmlSchemaContentProcessing
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | ドキュメント項目は検証されません。 |
| Skip | 1 | ドキュメント項目は適切に形成された XML で構成されている必要があり、スキーマによっては検証されません。 |
| Lax | 2 | 関連するスキーマが見つかった場合、ドキュメント項目は検証されます。そうでない場合はエラーは発生しません。 |
| Strict | 3 | スキーマプロセッサは、ドキュメント項目を検証するために、示された名前空間に関連付けられたスキーマを見つけなければなりません。 |

## 参照

* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)