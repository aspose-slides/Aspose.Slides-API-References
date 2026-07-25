---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: 書き込み保護されたプレゼンテーションに対して、変更パスワードが正しいかどうかを確認します。
type: docs
weight: 66
url: /ja/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) メソッド


書き込み保護されたプレゼンテーションに対して、変更パスワードが正しいかどうかを確認します。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 確認するパスワード。 |

### 戻り値

True if the presentation is write protected and the password is correct. False otherwise.

## 備考



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. このメソッドを呼び出す前に、[IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) プロパティを確認する必要があります。
1. パスワードが null または空の場合、このメソッドは false を返します。



## 参照

* クラス [String](../../../system/string/)
* クラス [IPresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)