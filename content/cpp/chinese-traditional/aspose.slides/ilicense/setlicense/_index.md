---
title: SetLicense()
second_title: Aspose.Slides for C++ API 參考文件
description: 為元件授權。
type: docs
weight: 1
url: /zh-hant/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) 方法

為元件授權。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 可以是完整或簡短的檔案名稱，或嵌入式資源的名稱。使用空字串可切換至評估模式。 |

## 備註

嘗試在以下位置尋找授權：

1. 明確路徑。

2. 元件組件所在的資料夾。

3. 用戶端呼叫組件所在的資料夾。

4. 入口組件所在的資料夾。

5. 用戶端呼叫組件中的嵌入式資源。

**注意:**在 .NET Compact Framework 上，僅嘗試在以下位置尋找授權：

1. 明確路徑。

2. 用戶端呼叫組件中的嵌入式資源。

在此範例中，系統會嘗試在包含元件的資料夾、呼叫組件的資料夾、入口組件的資料夾以及呼叫組件的嵌入式資源中，尋找名為 MyLicense.lic 的授權檔案。

```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) 方法

為元件授權。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含授權的資料流。 |

## 備註

使用此方法從資料流載入授權。

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ILicense](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)