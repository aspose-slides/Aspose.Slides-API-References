---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用の推奨設定を行います。bool を書き込みます。
type: docs
weight: 92
url: /ja/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) メソッド


読み取り専用の推奨設定を行います。**bool** を書き込みます。

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## 備考


以下のサンプルコードは、[Presentation](../../presentation/) PowerPoint を C# で [Aspose.Slides](../../) を使用して読み取り専用に設定する方法を示しています。 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)