---
title: File
second_title: Aspose.Slides for C++ API 參考文件
description: 提供操作檔案的方法。這是一個靜態型別，沒有實例服務。無論任何方式，都不應該建立其實例。
type: docs
weight: 261
url: /zh-hant/system.io/file/
---
## File 類別

提供操作檔案的方法。這是一個靜態型別，沒有實例服務。無論何種方式都不應該建立其實例。

```cpp
class File
```

## Methods

| 方法 | 說明 |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 將指定字串集合中的字串逐行寫入指定檔案，使用指定的編碼來附加。若指定的檔案不存在，則會建立。寫入所有字串後會關閉檔案。 |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的編碼，將指定字串附加到指定檔案。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | 建立一個 [StreamWriter](../streamwriter/) 物件，以 UTF-8 編碼將文字附加至指定檔案。若指定的檔案不存在，則會建立。 |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 將指定檔案複製到指定位置。若目標檔案已存在，參數會指示是否覆寫。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | 建立新檔案（或覆寫已有檔案），並使用指定的緩衝區大小和選項開啟以供讀寫存取。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | 建立新檔案或開啟已有檔案，以寫入 UTF-8 編碼的文字。 |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | 未實作。 |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | 刪除指定的檔案或目錄。 |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | 未實作。 |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 判斷指定的路徑是否指向現有檔案。 |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | 傳回指定實體的屬性。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 傳回指定實體的建立時間（本地時間）。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的建立時間（UTC 時間）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 傳回指定實體的最後存取時間（本地時間）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的最後存取時間（UTC 時間）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 傳回指定實體的最後寫入時間（本地時間）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的最後寫入時間（UTC 時間）。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將指定檔案移動至新位置。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | 以指定模式開啟指定檔案，供讀寫且不共享。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 以指定模式開啟指定檔案，使用指定的存取類型與共享選項。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | 以 'Open' 模式開啟指定檔案供唯讀，允許共享讀取。 |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 以 UTF-8 編碼開啟指定的現有檔案讀取文字，且不共享。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | 以 'OpenOrCreate' 模式開啟指定檔案供唯寫，且不共享。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | 將指定二進位檔案的內容讀取至位元組陣列。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符編碼，逐行讀取指定文字檔案的內容至字串陣列。 |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符編碼，將指定文字檔案的內容讀取至單一 [String](../../system/string/) 物件。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符編碼，逐行讀取指定文字檔案的內容，並傳回可列舉的字串集合，每個字串代表檔案內容的一行。 |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 以另一檔案取代一個檔案的內容，並為被取代的檔案建立備份。 |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | 設定指定檔案的指定屬性。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 未實作。 |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 未實作。 |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 未實作。 |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 未實作。 |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後寫入時間為本地時間。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後寫入時間為 UTC 時間。 |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 覆寫指定的二進位檔案，並寫入指定的位元組。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建立新文字檔或覆寫既有檔案，使用指定編碼將指定可列舉字串集合中的所有字串寫入檔案，每個字串佔新行。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建立新文字檔或覆寫既有檔案，使用指定編碼將指定字串陣列中的所有字串寫入檔案，每個字串佔新行。 |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建立新文字檔或覆寫既有檔案，使用指定編碼將指定字串的內容寫入檔案。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | 在讀寫檔案時緩衝的位元組數的預設值。 |

## 另請參閱

* 命名空間 [System::IO](../)
* 程式庫 [Aspose.Slides](../../)