---
title: ImageFormat
second_title: Aspose.Slides for C++ API 參考
description: "代表影像的檔案格式。此類別的物件應僅使用 System::MakeObject() 函式分配。絕不可在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 131
url: /zh-hant/system.drawing.imaging/imageformat/
---
## ImageFormat 類別

代表圖像的檔案格式。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class ImageFormat : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | 判斷目前物件與指定物件所代表的圖像格式是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 bitmap 圖像格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示增強型中繼檔案格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示可交換的 [Image](../../system.drawing/image/) 檔案（Exif）格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 [Graphics](../../system.drawing/graphics/) 互換格式（GIF）圖像格式。 |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | 傳回與目前物件所代表的圖像格式關聯的 GUID。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 [Windows](../../system.windows/) 圖示圖像格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 Joint Photographic Experts Group（JPEG）圖像格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示記憶體中 bitmap 的格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 W3C 可攜式網路 [Graphics](../../system.drawing/graphics/)（PNG）圖像格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 Tagged [Image](../../system.drawing/image/) 檔案格式（TIFF）圖像格式。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | 傳回指向 [ImageFormat](./) 物件的 shared pointer，該物件表示 [Windows](../../system.windows/) 中繼檔案（WMF）圖像格式。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似實作。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# 的 [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | 建立一個 [ImageFormat](./) 類別的實例，該實例代表與指定 GUID 關聯的圖像格式。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似實作。啟用自訂型別的克隆功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享引用計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為 weak pointer（而非 shared）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | 將此 [ImageFormat](./) 物件轉換為易讀的字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing::Imaging](../)
* 函式庫 [Aspose.Slides](../../)