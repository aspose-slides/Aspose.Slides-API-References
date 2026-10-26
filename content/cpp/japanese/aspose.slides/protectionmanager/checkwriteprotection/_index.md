---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが変更に対してパスワード保護されているかどうかを判定します。
type: docs
weight: 157
url: /ja/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) メソッド

プレゼンテーションが変更に対してパスワード保護されているかどうかを判定します。

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | チェックに使用するパスワード。 |

### 戻り値

パスワードが有効な場合は true、それ以外の場合は false。

## 備考

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. このメソッドを呼び出す前に、[ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) プロパティを確認する必要があります。
1. パスワードが null または空の場合、このメソッドは false を返します。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)