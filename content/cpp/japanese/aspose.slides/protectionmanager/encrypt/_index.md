---
title: Encrypt()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスワードでプレゼンテーションを暗号化します。
type: docs
weight: 105
url: /ja/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) メソッド

[Presentation](../../presentation/) を指定したパスワードで暗号化します。

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | パスワード。 |
## 備考

次のサンプルコードは、PowerPoint [Presentation](../../presentation/) を暗号化する方法を示しています。
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ProtectionManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)