---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: Binary Large Object BLOB（二進位大型物件）是一種以單一實體儲存的二進位資料——即 BLOB。
type: docs
url: /zh-hant/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object（BLOB）是一種以單一實體儲存的二進位資料——即 BLOB 可以是音訊、視訊或簡報本身。 在處理已儲存在簡報中或稍後以程式方式新增的 BLOB 時，會使用多種技術來最佳化記憶體使用。 使用 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 您可以變更 [IPresentation](../../com.aspose.slides/ipresentation) 實例生命週期中有關 BLOB 處理的各種行為層面。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用，但需要建立檔案的權限。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用，但需要建立檔案的權限。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 將建立暫存檔的根目錄路徑。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 將建立暫存檔的根目錄路徑。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。 |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。如果實例為擁有者，將鎖定來源。這有助於在處理 BLOB 時改善記憶體使用和效能，但在 Presentation 實例的生命週期內，來源（串流或檔案）無法變更。以下為範例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 將被拋出，因為 pres.pptx 在 Presentation 的生命週期內被鎖定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 物件釋放後，檔案會被解鎖且可以被刪除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**返回值：**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。如果實例為擁有者，將鎖定來源。這有助於在處理 BLOB 時改善記憶體使用和效能，但在 Presentation 實例的生命週期內，來源（串流或檔案）無法變更。以下為範例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 將被拋出，因為 pres.pptx 在 Presentation 的生命週期內被鎖定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 物件釋放後，檔案會被解鎖且可以被刪除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用，但需要建立檔案的權限。

--------------------

在簡報工作完成後，所有檔案將被刪除。

**返回值：**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用，但需要建立檔案的權限。

--------------------

在簡報工作完成後，所有檔案將被刪除。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

將建立暫存檔的根目錄路徑。預設使用系統暫存目錄。宿主程序應具備在該目錄建立檔案和資料夾的權限。

**返回值：**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

將建立暫存檔的根目錄路徑。預設使用系統暫存目錄。宿主程序應具備在該目錄建立檔案和資料夾的權限。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

此屬性定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 均會載入記憶體；僅當達到此限制時，才會採用替代機制（例如暫存檔）。將 BLOB 保留在記憶體中可最大化效能，但可能導致高記憶體使用。請使用此屬性根據您的環境或需求調整行為。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 設為 false，則此屬性會被忽略，因為此時記憶體是唯一可用的儲存位置，限制記憶體中的 BLOB 使用將不會產生效果。

--------------------

預設值為 629,145,600 位元組（600 MB）。

--------------------

您可以將此屬性設為零，但仍會保留少量最小記憶體。

**返回值：**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

此屬性定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 均會載入記憶體；僅當達到此限制時，才會採用替代機制（例如暫存檔）。將 BLOB 保留在記憶體中可最大化效能，但可能導致高記憶體使用。請使用此屬性根據您的環境或需求調整行為。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 設為 false，則此屬性會被忽略，因為此時記憶體是唯一可用的儲存位置，限制記憶體中的 BLOB 使用將不會產生效果。

--------------------

預設值為 629,145,600 位元組（600 MB）。

--------------------

您可以將此屬性設為零，但仍會保留少量最小記憶體。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |