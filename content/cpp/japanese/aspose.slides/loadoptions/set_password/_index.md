---
title: set_Password()
second_title: Aspose.Slides for C++ API リファレンス
description: "パスワードを設定します。System::String を書き込みます。"
type: docs
weight: 118
url: /ja/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) メソッド

パスワードを設定します。書き込みます [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## 備考

パスワード。

次のサンプルコードは、パスワードで保護された PowerPoint [Presentation](../../presentation/) を開く方法を示します。
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## 関連項目

* クラス [String](../../../system/string/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)