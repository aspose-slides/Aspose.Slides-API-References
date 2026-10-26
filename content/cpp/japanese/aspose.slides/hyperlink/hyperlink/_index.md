---
title: Hyperlink()
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクのインスタンスを作成します。
type: docs
weight: 339
url: /ja/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) コンストラクタ

Creates an instance of a hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) コンストラクタ

Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 対象スライド。 |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) コンストラクタ

Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | ソースハイパーリンク |
| targetFrame | [System::String](../../../system/string/) | 対象フレーム |
| tooltip | [System::String](../../../system/string/) | ツールチップテキスト |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Hyperlink](../)
* クラス [ISlide](../../islide/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)