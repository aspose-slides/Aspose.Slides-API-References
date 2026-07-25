---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: 書き込み保護されたプレゼンテーションに対して、変更用パスワードが正しいかどうかを確認します。
type: docs
weight: 66
url: /ja/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) メソッド


書き込み保護されたプレゼンテーションに対して、変更用パスワードが正しいかどうかをチェックします。

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | チェックするパスワード。 |

### 戻り値

プレゼンテーションが書き込み保護され、パスワードが正しい場合は True、そうでない場合は False が返されます。

## 備考



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. このメソッドを呼び出す前に [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) プロパティを確認すべきです。
1. パスワードが null または空文字列の場合、このメソッドは false を返します。



## 参照

* クラス [String](../../../system/string/)
* クラス [PresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)