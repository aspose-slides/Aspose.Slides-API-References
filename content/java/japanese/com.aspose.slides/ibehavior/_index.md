---
title: IBehavior
second_title: Aspose.Slides for Java API リファレンス
description: 効果の基本クラス動作を表します。
type: docs
url: /ja/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

効果の基本クラス動作を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | アニメーション ビヘイビアが蓄積されるかどうかを表します。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | アニメーション ビヘイビアが蓄積されるかどうかを表します。 |
| [getAdditive()](#getAdditive--) | 現在のアニメーション ビヘイビアが他の実行中のアニメーションと結合されるかどうかを表します。 |
| [setAdditive(int value)](#setAdditive-int-) | 現在のアニメーション ビヘイビアが他の実行中のアニメーションと結合されるかどうかを表します。 |
| [getProperties()](#getProperties--) | ビヘイビアのプロパティを表します。 |
| [getTiming()](#getTiming--) | 効果ビヘイビアのタイミング プロパティを表します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 効果ビヘイビアのタイミング プロパティを表します。 |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

アニメーション ビヘイビアが蓄積されるかどうかを表します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

アニメーション ビヘイビアが蓄積されるかどうかを表します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

現在のアニメーション ビヘイビアが他の実行中のアニメーションと結合されるかどうかを表します。読み取り/書き込み [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**戻り値:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

現在のアニメーション ビヘイビアが他の実行中のアニメーションと結合されるかどうかを表します。読み取り/書き込み [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

ビヘイビアのプロパティを表します。読み取り専用 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**戻り値:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

効果ビヘイビアのタイミング プロパティを表します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

効果ビヘイビアのタイミング プロパティを表します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |