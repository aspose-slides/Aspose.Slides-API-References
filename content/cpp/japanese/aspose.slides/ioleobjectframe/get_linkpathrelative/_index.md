---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API リファレンス
description: "リンクされたファイルが存在する場合は相対パスを返し、存在しない場合は空文字列を返します。読み取り専用 System::String."
type: docs
weight: 118
url: /ja/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() メソッド

リンクされたファイルが存在する場合は相対パスを返し、存在しない場合は空文字列を返します。読み取り専用 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## 備考

Ppt プレゼンテーションでは、Ole オブジェクトのリンクが相対表現になることがあります。

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 参照

* クラス [String](../../../system/string/)
* クラス [IOleObjectFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)