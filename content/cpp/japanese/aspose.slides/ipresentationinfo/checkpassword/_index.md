---
title: CheckPassword()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションがオープン パスワードで保護されている場合に、パスワードが正しいかどうかを確認します。
type: docs
weight: 53
url: /ja/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) メソッド

Checks whether a password is correct for a presentation protected with open password.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 確認するパスワード。 |

### 戻り値

プレゼンテーションがオープン パスワードで保護され、かつパスワードが正しい場合は True、そうでない場合は false を返します。

### 備考

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

パスワードが null または空文字列の場合、このメソッドは false を返します。

### 参照

* クラス [String](../../../system/string/)
* クラス [IPresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)