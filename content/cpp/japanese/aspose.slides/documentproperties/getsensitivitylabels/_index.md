---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタム ドキュメント プロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK メタデータ）。
type: docs
weight: 859
url: /ja/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() メソッド


カスタム ドキュメント プロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK Metadata）。

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## 備考


以下のコードは、カスタム ドキュメント プロパティから感度ラベル情報を最新の SensitivityLabels コレクションに移動する方法を示します:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// カスタム ドキュメント プロパティから感度ラベルを取得します
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // コレクションにラベルを追加します
    // ここでラベル情報の有効性（ラベルが利用可能かどうかなど）をチェックすることができます
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISensitivityLabel](../../isensitivitylabel/)
* クラス [DocumentProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)