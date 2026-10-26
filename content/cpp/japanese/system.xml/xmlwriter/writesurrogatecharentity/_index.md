---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、サロゲート文字ペアのサロゲート文字エンティティを生成し、書き込みます。
type: docs
weight: 261
url: /ja/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) メソッド

When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lowChar | char16_t | 低位サロゲートです。この値は0xDC00から0xDFFFの間である必要があります。 |
| highChar | char16_t | 高位サロゲートです。この値は0xD800から0xDBFFの間である必要があります。 |

## 参照

* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)