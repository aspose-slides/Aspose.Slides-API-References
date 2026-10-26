---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用の推奨設定を行います。bool を書き込みます。
type: docs
weight: 92
url: /ja/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) メソッド


読み取り専用の推奨設定を行います。**bool** を書き込みます。

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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