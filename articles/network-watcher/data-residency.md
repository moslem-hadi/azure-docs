---
title: Data residency for Azure Network Watcher | Microsoft Docs
description: This article will help you understand data residency for the Azure Network Watcher service.
services: network-watcher
documentationcenter: na
author: damendo
manager:
editor:
ms.service: network-watcher
ms.topic: article
ms.tgt_pltfrm: na
ms.workload:  infrastructure-services
ms.date: 06/16/2021
ms.author: damendo
ms.custom: engagement-fy23


---

# Data residency for Azure Network Watcher
With the exception of the Connection Monitor service, Azure Network Watcher doesn't store customer data.


## Connection Monitor data residency
The Connection Monitor service stores customer data. This data is automatically stored by Network Watcher in a single region. So Connection Monitor automatically satisfies in-region data residency requirements, including requirements specified on the [Trust Center](https://azuredatacentermap.azurewebsites.net/).

## Data residency
In Azure, the feature that enables storing customer data in a single region is currently available only in the Southeast Asia Region (Singapore) of the Asia Pacific geo and Brazil South (Sao Paulo State) Region of the Brazil geo. For all other regions, customer data is stored in Geo. For more information, see the [Trust Center](https://azuredatacentermap.azurewebsites.net/).

## Next steps

* Read an overview of [Network Watcher](./network-watcher-monitoring-overview.md).
