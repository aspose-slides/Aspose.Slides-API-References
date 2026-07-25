---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API リファレンス
description: ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID (CLSID) を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。
type: docs
weight: 1
url: /ja/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() メソッド


ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID (CLSID) を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## 参照

* クラス [Guid](../../../system/guid/)
* クラス [IPptOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)