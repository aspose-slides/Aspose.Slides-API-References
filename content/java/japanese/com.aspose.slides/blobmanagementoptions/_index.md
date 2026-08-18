---
title: BlobManagementOptions
second_title: Aspose.Slides for Java API リファレンス
description: BLOB の取り扱い規則やその他の BLOB 設定を管理するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/blobmanagementoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB の取り扱い規則やその他の BLOB 設定を管理するために使用できるオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | 新しいデフォルトの BLOB 管理オプションを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | このプロパティは、BLOB を操作している間に一時ファイルを作成できるかどうかを定義し、メモリ使用量を大幅に減らしますが、ファイル作成の権限が必要です。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | このプロパティは、BLOB を操作している間に一時ファイルを作成できるかどうかを定義し、メモリ使用量を大幅に減らしますが、ファイル作成の権限が必要です。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 一時ファイルが作成されるルートパスです。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 一時ファイルが作成されるルートパスです。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | メモリ内で BLOB が占有できる合計サイズ（バイト）最大値を定義します。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | メモリ内で BLOB が占有できる合計サイズ（バイト）最大値を定義します。 |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

新しいデフォルトの BLOB 管理オプションを作成します。

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できなくなります。

**戻り値:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより BLOB のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できなくなります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

このプロパティは、BLOB を操作している間に一時ファイルを作成できるかどうかを定義し、メモリ使用量を大幅に減らしますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの作業が完了した後、すべてのファイルが削除されます。

**戻り値:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

このプロパティは、BLOB を操作している間に一時ファイルを作成できるかどうかを定義し、メモリ使用量を大幅に減らしますが、ファイル作成の権限が必要です。

--------------------

プレゼンテーションの作業が完了した後、すべてのファイルが削除されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはそこにファイルやフォルダーを作成する権限を持っている必要があります。

**戻り値:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。ホスティングプロセスはそこにファイルやフォルダーを作成する権限を持っている必要があります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

メモリ内で BLOB が占有できる合計サイズ（バイト）最大値を定義します。デフォルトではすべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持することでパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して環境や要件に合わせた動作を調整してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一のストレージ位置となり、メモリ内 BLOB の使用量を制限しても効果がありません。

--------------------

既定値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、少量の最小メモリは確保されます。

**戻り値:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

メモリ内で BLOB が占有できる合計サイズ（バイト）最大値を定義します。デフォルトではすべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持することでパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して環境や要件に合わせた動作を調整してください。

--------------------

このプロパティは、\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) が false に設定されている場合は無視されます。メモリが唯一のストレージ位置となり、メモリ内 BLOB の使用量を制限しても効果がありません。

--------------------

既定値は 629,145,600 バイト（600 MB）です。

--------------------

このプロパティを 0 に設定することも可能ですが、少量の最小メモリは確保されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |