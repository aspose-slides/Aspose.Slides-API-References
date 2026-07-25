---
title: RemoveWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: このプレゼンテーションの書き込み保護を解除します。
type: docs
weight: 144
url: /ja/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() メソッド


このプレゼンテーションの書き込み保護を解除します。

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## 備考


このサンプルコードは、PowerPoint [Presentation](../../presentation/) から書き込み保護を解除する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)