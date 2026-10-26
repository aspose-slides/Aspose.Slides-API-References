---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのすべてのカスタム データ パーツを返します。読み取り専用 ICustomXmlPart[]。
type: docs
weight: 287
url: /ja/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() メソッド

プレゼンテーションのすべてのカスタム データ パーツを返します。読み取り専用 [ICustomXmlPart](../../icustomxmlpart/)[]。

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## 備考

次の例は、PowerPoint [Presentation](../) からすべてのカスタム XML パーツをクリアする方法を示します。

```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ICustomXmlPart](../../icustomxmlpart/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)