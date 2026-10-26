---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが変更のためにパスワードで保護されているかどうかを判定します。
type: docs
weight: 157
url: /ja/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) メソッド


プレゼンテーションが変更に対してパスワードで保護されているかどうかを判定します。

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 確認用のパスワード。 |

### 戻り値

パスワードが有効な場合は true、そうでない場合は false。
## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. このメソッドを呼び出す前に [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) プロパティを確認する必要があります。
1. パスワードが null または空文字列の場合、このメソッドは false を返します。


## 参照

* クラス [String](../../../system/string/)
* クラス [IProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)