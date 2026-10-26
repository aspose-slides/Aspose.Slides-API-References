---
title: XmlSeverityType
second_title: Aspose.Slides for C++ API リファレンス
description: 検証イベントの重大度を表します。
type: docs
weight: 1080
url: /ja/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

検証イベントの重大度を表します。

```cpp
enum class XmlSeverityType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Error | 0 | インスタンス文書の検証時に検証エラーが発生したことを示します。これは文書型定義 (DTDs) および XML [Schema](../) 定義言語 (XSD) スキーマに適用されます。World Wide [Web](../../system.web/) Consortium (W3C) の妥当性制約はエラーとみなされます。検証イベントハンドラが作成されていない場合、エラーは例外をスローします。 |
| Warning | 1 | エラーではない検証イベントが発生したことを示します。DTD が存在しない場合や XML [Schema](../) がなく特定の要素や属性を検証できない場合に通常警告が発行されます。エラーとは異なり、検証イベントハンドラがない場合でも警告は例外をスローしません。 |

## 参照

* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)