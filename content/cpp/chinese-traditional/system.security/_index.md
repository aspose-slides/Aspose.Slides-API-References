---
title: "System::Security"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 807
url: /zh-hant/system.security/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | 安全字串，代表應保密的文字。此類別不會加密內部資料。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行期錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [SecureStringMarshal](./securestringmarshal/) | 用於配置與複製非受管理記憶體區塊的方法集合。 |
| [SecurityElement](./securityelement/) | 用於編碼安全物件的 XML 物件模型。未實作。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行期錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
## 型別定義

| 型別別名 | 說明 |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) 指標類型。 |