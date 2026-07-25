---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタムドキュメントプロパティ (Microsoft Information Protection SDK メタデータ) から感度ラベルの配列を取得します。
type: docs
weight: 872
url: /ja/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() メソッド

カスタムドキュメントプロパティ (Microsoft Information Protection SDK Metadata) から感度ラベルの配列を取得します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## 備考

以下のコードは、カスタムドキュメントプロパティから感度ラベル情報を最新の SensitivityLabels コレクションに移動する方法を示しています。

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// カスタムドキュメントプロパティから感度ラベルを取得
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // ラベルをコレクションに追加
    // ここでラベル情報の有効性（ラベルが利用可能か等）をチェックできます
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISensitivityLabel](../../isensitivitylabel/)
* クラス [IDocumentProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)