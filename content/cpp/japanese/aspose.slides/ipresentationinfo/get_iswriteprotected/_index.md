---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API リファレンス
description: バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。
type: docs
weight: 27
url: /ja/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() メソッド


バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## 備考



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


プレゼンテーションが開くためのパスワードで保護されている場合、プロパティ値は NotDefined になります。[NullableBool](../../nullablebool/) 列挙型を参照してください。 
## 参照

* 列挙型 [NullableBool](../../nullablebool/)
* クラス [IPresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)