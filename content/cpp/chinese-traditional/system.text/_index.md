---
title: "System::Text"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 976
url: /zh-hant/system.text/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/) | 代表 ASCII 編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Decoder](./decoder/) | 封裝將位元組序列解碼為字元序列的功能。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderExceptionFallback](./decoderexceptionfallback/) | 提供拋出例外的備援策略。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/) | [Buffer](../system/buffer/) 用於拋出例外的解碼備援策略。實際上不會儲存任何資料，而是直接拋出例外。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderFallback](./decoderfallback/) | 提供備援 API 以處理解碼錯誤。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderFallbackBuffer](./decoderfallbackbuffer/) | 為備援實作提供緩衝區。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderReplacementFallback](./decoderreplacementfallback/) | 提供以虛擬符號取代錯誤符號的備援策略。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DecoderReplacementFallbackBuffer](./decoderreplacementfallbackbuffer/) | [Buffer](../system/buffer/) 用於取代解碼備援策略。 |
| [Details_DecoderFallbackException](./details_decoderfallbackexception/) | 解碼失敗時由 [DecoderExceptionFallback](./decoderexceptionfallback/) 拋出的例外。切勿手動建立此類別的實例，請改用 DecoderFallbackException 類別。切勿將 DecoderFallbackException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [Details_EncoderFallbackException](./details_encoderfallbackexception/) | 編碼失敗時由 [EncoderExceptionFallback](./encoderexceptionfallback/) 拋出的例外。切勿手動建立此類別的實例，請改用 EncoderFallbackException 類別。切勿將 EncoderFallbackException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [Encoder](./encoder/) | 封裝將字元序列編碼為位元組序列的功能。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderExceptionFallback](./encoderexceptionfallback/) | 提供拋出例外的備援策略。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderExceptionFallbackBuffer](./encoderexceptionfallbackbuffer/) | [Buffer](../system/buffer/) 用於拋出例外的編碼備援策略。實際上不會儲存任何資料，而是直接拋出例外。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderFallback](./encoderfallback/) | 提供備援 API 以處理編碼錯誤。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderFallbackBuffer](./encoderfallbackbuffer/) | 為備援實作提供緩衝區。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderReplacementFallback](./encoderreplacementfallback/) | 提供以虛擬符號取代錯誤符號的備援策略。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncoderReplacementFallbackBuffer](./encoderreplacementfallbackbuffer/) | [Buffer](../system/buffer/) 用於取代編碼備援策略。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Encoding](./encoding/) | [Encoding](./encoding/) 服務。 |
| [EncodingDecoder](./encodingdecoder/) | [Decoder](./decoder/) 使用編碼物件進行解碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncodingEncoder](./encodingencoder/) | [Encoder](./encoder/) 使用編碼物件進行編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EncodingInfo](./encodinginfo/) | 關於編碼的簡要資訊。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICUDecoder](./icudecoder/) | [Decoder](./decoder/) 使用 ICU 進行解碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICUEncoder](./icuencoder/) | [Encoder](./encoder/) 使用 ICU 進行編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICUEncoding](./icuencoding/) | 基於 ICU 的編碼實作。僅供內部使用。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Latin1Encoding](./latin1encoding/) | Latin1 編碼支援。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [StringBuilder](./stringbuilder/) | [Buffer](../system/buffer/) 用於逐段累積字串。此類型可以在堆疊作為值型別或在堆上使用 [System::MakeObject()](../system/makeobject/) 函式分配。一旦物件被分配，切勿混用這兩種情況：擁有指向堆疊分配物件的 [SmartPtr](../system/smartptr/) 指標是嚴格禁止的。 |
| [UnicodeEncoding](./unicodeencoding/) | Unicode 編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [UTF32Encoding](./utf32encoding/) | UTF-32 編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [UTF7Encoding](./utf7encoding/) | UTF-7 編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [UTF8Encoding](./utf8encoding/) | UTF-8 編碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言錯誤。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [NormalizationForm](./normalizationform/) | 定義如何正規化 Unicode 字串。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [DecoderFallbackException](./decoderfallbackexception/) |  |
| [EncoderFallbackException](./encoderfallbackexception/) |  |
| [ICUEncodingPtr](./icuencodingptr/) | ICU 編碼指標。