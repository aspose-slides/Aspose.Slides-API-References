---
title: CheckPassword()
second_title: Aspose.Slides for C++ API リファレンス
description: オープン パスワードで保護されたプレゼンテーションに対して、パスワードが正しいかどうかを確認します。
type: docs
weight: 53
url: /ja/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) メソッド

オープン パスワードで保護されたプレゼンテーションに対して、パスワードが正しいかどうかを確認します。

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 確認するパスワード。 |

### 戻り値

True if the presentation is protected with open password and the password is correct and false otherwise.

## 備考

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

パスワードが null または空の場合、このメソッドは false を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [PresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)