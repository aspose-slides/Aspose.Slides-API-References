---
title: BlobManagementOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示可用於管理 BLOB 處理規則及其他 BLOB 設定的選項。
type: docs
url: /zh-hant/com.aspose.slides/blobmanagementoptions/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

代表可用於管理 BLOB 處理規則及其他 BLOB 設定的選項。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | 建立新的預設 BLOB 管理選項。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源-檔案或串流的擁有者。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源-檔案或串流的擁有者。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用量，但需要建立檔案的權限。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用量，但需要建立檔案的權限。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 建立暫存檔的根路徑。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 建立暫存檔的根路徑。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。 |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


建立新的預設 BLOB 管理選項。

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源-檔案或串流的擁有者。如果實例是擁有者，則會鎖定來源。這有助於在處理 BLOB 時改善記憶體使用量與效能，但在 Presentation 實例生命週期內無法變更來源（串流或檔案）。

**回傳值:**  
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源-檔案或串流的擁有者。如果實例是擁有者，則會鎖定來源。這有助於在處理 BLOB 時改善記憶體使用量與效能，但在 Presentation 實例生命週期內無法變更來源（串流或檔案）。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用量，但需要建立檔案的權限。

--------------------

所有檔案將在完成簡報的操作後被刪除。

**回傳值:**  
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


此屬性定義在處理 BLOB 時是否可以建立暫存檔，這會大幅降低記憶體使用量，但需要建立檔案的權限。

--------------------

所有檔案將在完成簡報的操作後被刪除。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


建立暫存檔的根路徑。預設會使用系統暫存目錄。主機進程應具備在該處建立檔案和資料夾的權限。

**回傳值:**  
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


建立暫存檔的根路徑。預設會使用系統暫存目錄。主機進程應具備在該處建立檔案和資料夾的權限。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 會載入記憶體；僅在達到此上限時才會採用替代機制（例如暫存檔）。將 BLOB 保留在記憶體中可提升效能，但可能導致記憶體使用量過高。請依您的環境或需求調整此屬性。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 設為 false，則此屬性會被忽略，因為此時記憶體是唯一的儲存位置，限制記憶體中 BLOB 的使用不會產生影響。

--------------------

預設值為 629,145,600 位元組（600 MB）。

--------------------

您可以將此屬性設定為 0，但仍會保留少量的最小記憶體。

**回傳值:**  
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 會載入記憶體；僅在達到此上限時才會採用替代機制（例如暫存檔）。將 BLOB 保留在記憶體中可提升效能，但可能導致記憶體使用量過高。請依您的環境或需求調整此屬性。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 設為 false，則此屬性會被忽略，因為此時記憶體是唯一的儲存位置，限制記憶體中 BLOB 的使用不會產生影響。

--------------------

預設值為 629,145,600 位元組（600 MB）。

--------------------

您可以將此屬性設定為 0，但仍會保留少量的最小記憶體。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |