---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /ja/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object (BLOB) は、単一のエンティティとして保存されるバイナリデータです。つまり、BLOB はオーディオ、ビデオ、またはプレゼンテーション自体になることがあります。BLOB はプレゼンテーションに既に保存されている場合や、後でプログラムで追加される場合があり、メモリ使用量を最適化するためにさまざまな手法が使用されます。[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) を使用すると、[IPresentation](../../com.aspose.slides/ipresentation) インスタンスのライフタイムにおける BLOB の取り扱いに関するさまざまな動作側面を変更できます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | このプロパティは、Presentation クラスのインスタンスがライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | このプロパティは、Presentation クラスのインスタンスがライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。これによりメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。これによりメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 一時ファイルが作成されるルートパスです。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 一時ファイルが作成されるルートパスです。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | メモリ内で BLOB が占有できる最大合計サイズ（バイト単位）を定義します。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | メモリ内で BLOB が占有できる最大合計サイズ（バイト単位）を定義します。 |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

このプロパティは、Presentation クラスのインスタンスがライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB を扱う際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンスのライフタイム中はソース（ストリームまたはファイル）を変更できません。以下は例です：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException がスローされます。これは pres.pptx が Presentation のライフタイム中ロックされているためです。
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation オブジェクトが破棄された後、ファイルのロックが解除され削除可能になります。
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**戻り値:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

このプロパティは、Presentation クラスのインスタンスがライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB を扱う際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンスのライフタイム中はソース（ストリームまたはファイル）を変更できません。以下は例です：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException がスローされます。これは pres.pptx が Presentation のライフタイム中ロックされているためです。
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation オブジェクトが破棄された後、ファイルのロックが解除され削除可能になります。
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。これによりメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの作業が終了した後、すべてのファイルは削除されます。

**戻り値:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。これによりメモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの作業が終了した後、すべてのファイルは削除されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはそこにファイルやフォルダーを作成する権限を持っている必要があります。

**戻り値:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはそこにファイルやフォルダーを作成する権限を持っている必要があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

このプロパティは、メモリ内で BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリに読み込まれます。この上限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持することでパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。

--------------------

このプロパティは、#isTemporaryFilesAllowed.isTemporaryFilesAllowed/#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保管場所となり、メモリ内 BLOB の使用を制限しても効果がありません。

--------------------

既定値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することもできますが、最小限のメモリは確保されます。

**戻り値:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

このプロパティは、メモリ内で BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリに読み込まれます。この上限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持することでパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。

--------------------

このプロパティは、#isTemporaryFilesAllowed.isTemporaryFilesAllowed/#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保管場所となり、メモリ内 BLOB の使用を制限しても効果がありません。

--------------------

既定値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することもできますが、最小限のメモリは確保されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |