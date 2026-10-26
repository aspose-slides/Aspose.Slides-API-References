---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: サロゲート文字ペアのサロゲート文字エンティティを生成して書き込みます。
type: docs
weight: 391
url: /ja/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) メソッド

サロゲート文字ペアのサロゲート文字エンティティを生成して書き込みます。

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lowChar | char16_t | 低位サロゲートです。これは **0xDC00** から **0xDFFF** までの値でなければなりません。 |
| highChar | char16_t | 高位サロゲートです。これは **0xD800** から **0xDBFF** までの値でなければなりません。 |

## 参照

* クラス [XmlTextWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)