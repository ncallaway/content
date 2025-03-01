---
title: OfflineAudioCompletionEvent()
slug: Web/API/OfflineAudioCompletionEvent/OfflineAudioCompletionEvent
tags:
  - API
  - Audio
  - Constructor
  - OfflineAudioCompletionEvent
  - Reference
  - Web Audio API
browser-compat: api.OfflineAudioCompletionEvent.OfflineAudioCompletionEvent
---
{{APIRef("Web Audio API")}}

The **`OfflineAudioCompletionEvent()`** constructor of the [Web Audio API](/en-US/docs/Web/API/Web_Audio_API) creates a new
{{domxref("OfflineAudioCompletionEvent")}} object instance.

> **Note:** You wouldn't generally use the constructor manually.
> `OfflineAudioCompletionEvent`s are dispatched to
> {{domxref("OfflineAudioContext")}} instances for legacy reasons.

## Syntax

```js
new OfflineAudioCompletionEvent(type, init)
```

### Parameters

- `type` {{optional_inline}}
  - : A {{domxref("DOMString")}} representing the type of object to create.
- `init` {{optional_inline}}

  - : Options are as follows:

    - `renderedBuffer`
      - : The rendered {{domxref("AudioBuffer")}}
        containing the audio data.

### Return value

A new {{domxref("OfflineAudioCompletionEvent")}} object instance.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
