---
title: SetWriteProtection()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。
type: docs
weight: 131
url: /ja/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) method

指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | パスワード。 |

## 備考

次のサンプルコードは、プレゼンテーションに書き込み保護を設定する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)