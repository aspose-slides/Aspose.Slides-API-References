---
title: get_Password()
second_title: Aspose.Slides の C++ API リファレンス
description: "パスワードを取得します。System::String を参照してください。"
type: docs
weight: 105
url: /ja/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() メソッド


パスワードを取得します。参照 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## 備考


パスワード。

以下のサンプルコードは、パスワードで保護されたPowerPoint [Presentation](../../presentation/)を開く方法を示しています。 
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