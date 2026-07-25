---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用の推奨設定を取得します。bool を読み取ります。
type: docs
weight: 79
url: /ja/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() メソッド

読み取り専用の推奨設定を取得します。**bool** を返します。

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## 備考

次のサンプルコードは、[Aspose.Slides](../../) を使用して C# で PowerPoint [Presentation](../../presentation/) を読み取り専用に設定する方法を示します。
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)