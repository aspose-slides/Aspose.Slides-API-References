---
title: License()
second_title: Aspose.Slides for C++ API 參考
description: 初始化此類別的新執行個體。
type: docs
weight: 1
url: /zh-hant/aspose.slides/license/license/
---
## License::License() 建構函式

初始化此類別的新執行個體。

```cpp
Aspose::Slides::License::License()
```

## 備註

在此範例中，系統將嘗試在包含元件的資料夾、包含呼叫的組件的資料夾、入口組件的資料夾中尋找名為 MyLicense.lic 的授權檔，然後在呼叫的組件的嵌入式資源中查找。

```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## 另請參閱

* 類別 [License](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)