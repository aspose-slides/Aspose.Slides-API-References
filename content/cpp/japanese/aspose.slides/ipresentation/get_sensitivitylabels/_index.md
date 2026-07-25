---
title: get_SensitivityLabels()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 ISensitivityLabelCollection.
type: docs
weight: 391
url: /ja/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() メソッド

プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## 備考

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// 適用されたラベルを出力
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// 新しいラベルを追加
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// ポリシーから感度ラベル ID を取得
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// ポリシーから Azure AD サイト識別子を取得
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* クラス [IPresentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)