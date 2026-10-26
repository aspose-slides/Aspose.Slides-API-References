---
title: get_Standalone()
second_title: Aspose.Slides for C++ API リファレンス
description: standalone 属性の値を返します。
type: docs
weight: 40
url: /ja/system.xml/xmldeclaration/get_standalone/
---
## XmlDeclaration::get_Standalone() メソッド


standalone 属性の値を返します。

```cpp
String System::Xml::XmlDeclaration::get_Standalone()
```


### 戻り値

有効な値は、XML ドキュメントに必要なすべてのエンティティ宣言がドキュメント内に含まれている場合は **yes**、外部ドキュメント型定義 (DTD) が必要な場合は **no** です。XML 宣言に standalone 属性が存在しない場合、このメソッドは [String::Empty](../../../system/string/empty/) を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlDeclaration](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)