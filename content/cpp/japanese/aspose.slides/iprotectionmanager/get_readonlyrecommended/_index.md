---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用推奨設定を取得します。bool を読み取ります。
type: docs
weight: 79
url: /ja/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() method


読み取り専用推奨設定を取得します。**bool** を読み取ります。

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)