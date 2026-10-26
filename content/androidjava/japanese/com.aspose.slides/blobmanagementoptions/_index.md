---
title: BlobManagementOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: BLOB の処理ルールやその他の BLOB 設定を管理するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**  
継承:

java.lang.Object

**All Implemented Interfaces:**  
実装されたすべてのインターフェイス:

[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB の処理ルールおよびその他の BLOB 設定を管理するために使用できるオプションを表します。

## コンストラクター

| Constructor | Description |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | 新しい既定の BLOB 管理オプションを作成します。 |

## メソッド

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | このプロパティは、Presentation クラスのインスタンスがその存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | このプロパティは、Presentation クラスのインスタンスがその存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルを使用するとメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルを使用するとメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはその場所にファイルやフォルダーを作成する権限を持っている必要があります。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはその場所にファイルやフォルダーを作成する権限を持っている必要があります。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | すべての BLOB がメモリ内で占めることのできる合計サイズの上限（バイト単位）を定義します。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | すべての BLOB がメモリ内で占めることのできる合計サイズの上限（バイト単位）を定義します。 |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

新しい既定の BLOB 管理オプションを作成します。

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

このプロパティは、Presentation クラスのインスタンスがその存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB を扱う際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できません。

**Returns:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

このプロパティは、Presentation クラスのインスタンスがその存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB を扱う際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できません。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルを使用するとメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの操作が完了した後、すべてのファイルは削除されます。

**Returns:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルを使用するとメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの操作が完了した後、すべてのファイルは削除されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはその場所にファイルやフォルダーを作成する権限を持っている必要があります。

**Returns:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはその場所にファイルやフォルダーを作成する権限を持っている必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

すべての BLOB がメモリ内で占めることのできる合計サイズの上限（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされますが、この上限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持するとパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を設定してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、メモリ内 BLOB 使用量の制限に効果がなくなるためです。

--------------------

デフォルト値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、最小限のメモリは確保されます。

**Returns:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

すべての BLOB がメモリ内で占めることのできる合計サイズの上限（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされますが、この上限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持するとパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を設定してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、メモリ内 BLOB 使用量の制限に効果がなくなるためです。

--------------------

デフォルト値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、最小限のメモリは確保されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |