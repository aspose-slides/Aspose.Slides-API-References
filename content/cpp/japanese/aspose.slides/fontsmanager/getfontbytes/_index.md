---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォントスタイルとフォントデータに対応するフォントデータを表すバイト配列を取得します。
type: docs
weight: 131
url: /ja/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) メソッド

Retrieves the byte array representing the font data for a specified font style and font data.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | フォント [IFontData](../../ifontdata/) に関する情報を含むフォントデータオブジェクト。 |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | データを取得するフォントのスタイル [FontStyleType](../../fontstyletype/)。 |

### 戻り値

指定されたフォントスタイルのフォントデータを含むバイト配列です。フォントデータまたはスタイルが見つからない場合、null を返します。

## 備考




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 関連項目

* 列挙体 [FontStyleType](../../fontstyletype/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontData](../../ifontdata/)
* クラス [FontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)