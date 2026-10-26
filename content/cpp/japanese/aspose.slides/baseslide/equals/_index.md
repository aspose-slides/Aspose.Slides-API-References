---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 二つの IBaseSlide インスタンスが等しいかどうかを判定します。戻り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定等が等しい場合、スライドは等しいとみなされます。比較は一意の識別子値（例: SlideId）や動的コンテンツ（例: 現在の日付値）を考慮しません。Date Placeholder の現在の日付値。
type: docs
weight: 170
url: /ja/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) メソッド


二つの [IBaseSlide](../../ibaseslide/) インスタンスが等しいかどうかを判定します。戻り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定などが等しい場合、スライドは等しいとみなされます。比較は一意の識別子値（例: SlideId）や動的コンテンツ（例: 現在の日付値）を考慮しません。Date [Placeholder](../../placeholder/)。

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | 現在の [IBaseSlide](../../ibaseslide/) と比較するための [IBaseSlide](../../ibaseslide/)。 |

### 戻り値

**true** if the specified [IBaseSlide](../../ibaseslide/) is equal to the current [IBaseSlide](../../ibaseslide/); otherwise, **false**。

## 補足

以下の例は、2つのスライドを比較する方法を示しています。 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBaseSlide](../../ibaseslide/)
* クラス [BaseSlide](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)