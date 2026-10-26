---
title: ValidationType
second_title: Aspose.Slides for C++ API リファレンス
description: 実行する検証のタイプを指定します。
type: docs
weight: 729
url: /ja/system.xml/validationtype/
---
## ValidationType 列挙型

実行する検証のタイプを指定します。

```cpp
enum class ValidationType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 検証は行われず、検証エラーもスローされません。この設定は XML 1.0 に準拠した非検証パーサーを作成します。 |
| Auto | 1 | DTD またはスキーマ情報が見つかった場合に検証を行います。 |
| DTD | 2 | DTD に従って検証します。 |
| XDR | 3 | インライン XDR スキーマを含む XML-Data Reduced (XDR) スキーマに従って検証します。XDR スキーマは **x-schema** 名前空間プレフィックスまたは [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) 値を使用して認識されます。 |
| Schema | 4 | インライン XML スキーマを含む XML [Schema](../../system.xml.schema/) 定義言語 (XSD) スキーマに従って検証します。XML スキーマは **schemaLocation** 属性または提供された **Schemas** を使用して名前空間 URI に関連付けられます。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)