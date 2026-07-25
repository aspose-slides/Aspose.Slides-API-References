---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に署名を追加します。
type: docs
weight: 53
url: /ja/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature>) メソッド

コレクションの末尾に署名を追加します。

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)<[IDigitalSignature](../../idigitalsignature/)> | 追加する署名。 |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDigitalSignature](../../idigitalsignature/)
* クラス [DigitalSignatureCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)