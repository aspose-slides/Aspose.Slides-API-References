---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API リファレンス
description: VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。読み取り専用 bool。
type: docs
weight: 40
url: /ja/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() メソッド


VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。読み取り専用 **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## 参照

* クラス [VbaProject](../)
* 名前空間 [Aspose::Slides::Vba](../../)
* ライブラリ [Aspose.Slides](../../../)