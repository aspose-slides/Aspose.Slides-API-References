---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API リファレンス
description: バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。
type: docs
weight: 27
url: /ja/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() メソッド

バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## 備考



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

プレゼンテーションが開くためのパスワードで保護されている場合、プロパティ値は NotDefined と等しいです。

## 参照

* Enum [NullableBool](../../nullablebool/)
* クラス [PresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)