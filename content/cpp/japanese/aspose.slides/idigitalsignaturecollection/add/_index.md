---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に署名を追加します。
type: docs
weight: 14
url: /ja/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) メソッド


コレクションの末尾に署名を追加します。

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | 追加する署名。 |
## 備考



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDigitalSignature](../../idigitalsignature/)
* クラス [IDigitalSignatureCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)