---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API リファレンス
description: バインドされたプレゼンテーションが開く際にパスワードで保護されているかどうかを示す値を取得します。
type: docs
weight: 14
url: /ja/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() メソッド


バインドされたプレゼンテーションが開く際にパスワードで保護されているかどうかを示す値を取得します。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## 備考



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## 参照

* クラス [IPresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)