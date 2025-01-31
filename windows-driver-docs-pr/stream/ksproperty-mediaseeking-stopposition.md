---
title: KSPROPERTY_MEDIASEEKING_STOPPOSITION
description: The KSPROPERTY_MEDIASEEKING_STOPPOSITION property retrieves the stop media time on a filter.
keywords: ["KSPROPERTY_MEDIASEEKING_STOPPOSITION Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_MEDIASEEKING_STOPPOSITION
api_location:
- ks.h
api_type:
- HeaderDef
ms.date: 10/22/2021
ms.localizationpriority: medium
---

# KSPROPERTY_MEDIASEEKING_STOPPOSITION

The **KSPROPERTY_MEDIASEEKING_STOPPOSITION** property retrieves the stop media time on a filter.

## Usage Summary Table

| Get | Set | Target | Property Descriptor Type | Property Value Type |
|--|--|--|--|--|
| Yes | No | Filter | [**KSPROPERTY**](/windows-hardware/drivers/stream/ksproperty-structure) | LONGLONG |

## Remarks

The stop media time is the time that can be set if a stop time is supported by the filter.

## Requirements

**Header:** ks.h (include Ks.h)

## See also

[KSPROPSETID_MediaSeeking](kspropsetid-mediaseeking.md)

[**KSPROPERTY**](/windows-hardware/drivers/stream/ksproperty-structure)
