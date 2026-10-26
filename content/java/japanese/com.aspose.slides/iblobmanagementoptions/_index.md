---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API リファレンス
description: バイナリ大規模オブジェクト（BLOB）は、単一のエンティティとして格納されるバイナリデータです。
type: docs
url: /ja/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

バイナリ大規模オブジェクト（BLOB）は、単一のエンティティとして格納されるバイナリデータです。すなわち、BLOB は音声、動画、またはプレゼンテーションそのものになることがあります。BLOB を操作する際のメモリ使用量を最適化するために、さまざまな手法が使用されます。BLOB はプレゼンテーションにすでに格納されている場合や、後からプログラムで追加される場合があります。[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) を使用すると、[IPresentation](../../com.aspose.slides/ipresentation) インスタンスのライフタイムに関する BLOB の取り扱いのさまざまな動作側面を変更できます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | このプロパティは、Presentation クラスのインスタンスがそのライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | このプロパティは、Presentation クラスのインスタンスがそのライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | このプロパティは、BLOB を操作中に一時ファイルを作成できるかどうかを定義します。これによりメモリ使用量が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | このプロパティは、BLOB を操作中に一時ファイルを作成できるかどうかを定義します。これによりメモリ使用量が大幅に減少しますが、ファイル作成の権限が必要です。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 一時ファイルが作成されるルートパスです。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 一時ファイルが作成されるルートパスです。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | メモリ内で BLOB が占有できる合計最大サイズ（バイト単位）を定義します。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | メモリ内で BLOB が占有できる合計最大サイズ（バイト単位）を定義します。 |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

このプロパティは、Presentation クラスのインスタンスがそのライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより、BLOB を操作する際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス期間中はソース（ストリームまたはファイル）を変更できません。以下は例です：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Presentation のライフタイム中に pres.pptx がロックされているため、IOException がスローされます
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation オブジェクトが破棄された後、ファイルのロックが解除され、削除できるようになります
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**戻り値:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

このプロパティは、Presentation クラスのインスタンスがそのライフタイム中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより、BLOB を操作する際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス期間中はソース（ストリームまたはファイル）を変更できません。以下は例です：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Presentation のライフタイム中に pres.pptx がロックされているため、IOException がスローされます
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation オブジェクトが破棄された後、ファイルのロックが解除され、削除できるようになります
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

このプロパティは、BLOB を操作中に一時ファイルを作成できるかどうかを定義します。これによりメモリ使用量が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

すべてのファイルは、プレゼンテーションの作業が完了した後に削除されます。

**戻り値:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

このプロパティは、BLOB を操作中に一時ファイルを作成できるかどうかを定義します。これによりメモリ使用量が大幅に減少しますが、ファイル作成の権限が必要です。

--------------------

すべてのファイルは、プレゼンテーションの作業が完了した後に削除されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

一時ファイルが作成されるルートパスです。システムの一時ディレクトリがデフォルトで使用されます。ホスティングプロセスは、そこにファイルとフォルダーを作成する権限を持っている必要があります。

**戻り値:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

一時ファイルが作成されるルートパスです。システムの一時ディレクトリがデフォルトで使用されます。ホスティングプロセスは、そこにファイルとフォルダーを作成する権限を持っている必要があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

メモリ内で BLOB が占有できる合計最大サイズ（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。環境や要件に合わせて動作を調整するためにこのプロパティを使用してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、メモリ内 BLOB 使用量の制限は効果を持ちません。

--------------------

デフォルト値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、最小限のメモリは確保されます。

**戻り値:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

メモリ内で BLOB が占有できる合計最大サイズ（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。環境や要件に合わせて動作を調整するためにこのプロパティを使用してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、メモリ内 BLOB 使用量の制限は効果を持ちません。

--------------------

デフォルト値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、最小限のメモリは確保されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |