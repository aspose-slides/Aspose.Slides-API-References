---
title: SetLicense()
second_title: Aspose.Slides for C++ API 參考文件
description: 為元件授權。
type: docs
weight: 14
url: /zh-hant/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) 方法


為元件授權。

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 可以是完整或簡短的檔案名稱，或是嵌入式資源的名稱。使用空字串可切換至評估模式。 |
## 備註



嘗試在以下位置尋找授權：

1. 明確路徑。

2. 元件組件所在的資料夾。

3. 客戶端呼叫組件所在的資料夾。

4. 入口組件所在的資料夾。

5. 客戶端呼叫組件中的嵌入式資源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明確路徑。

2. 客戶端呼叫組件中的嵌入式資源。

在此範例中，系統會嘗試在包含元件的資料夾、包含呼叫組件的資料夾、入口組件的資料夾，以及呼叫組件的嵌入式資源中，尋找名為 MyLicense.lic 的授權檔案。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) 方法


為元件授權。

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含授權的資料流。 |
## 備註



使用此方法從資料流載入授權。


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [License](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)