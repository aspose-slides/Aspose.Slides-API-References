---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。
type: docs
weight: 131
url: /ja/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) メソッド

指定されたフォントスタイルとフォントデータに対応するフォントデータを表すバイト配列を取得します。

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | フォント[IFontData](../../ifontdata/)に関する情報を含むフォントデータオブジェクトです。 |
| fontStyle | [FontStyleType](../../fontstyletype/) | データを取得するフォントのスタイル[FontStyleType](../../fontstyletype/)です。 |

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

## 参照

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)