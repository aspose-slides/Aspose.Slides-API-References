---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたプレフィックスに対する名前空間 URI を返します。
type: docs
weight: 118
url: /ja/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) method

指定されたプレフィックスに対応する名前空間 URI を返します。

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間 URI を持つプレフィックス。デフォルト名前空間に一致させるには、[String::Empty](../../../system/string/empty/) を渡します。 |

### 戻り値

マッピングされた名前空間が存在しない場合は **nullptr**、それ以外の場合は **prefix** の名前空間 URI を返します。戻り値の文字列はアトミック化されています。アトミック化された文字列の詳細については、[XmlNameTable](../../xmlnametable/) クラスをご参照ください。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNamespaceManager](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)