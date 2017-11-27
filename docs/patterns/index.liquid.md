---
title: "云设计模式"
description: "Microsoft Azure 的云设计模式"
keywords: Azure
ms.openlocfilehash: 264b8296a428f9c1b87314b782efcabc89cf010f
ms.sourcegitcommit: b0482d49aab0526be386837702e7724c61232c60
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/14/2017
---
# <a name="cloud-design-patterns"></a><span data-ttu-id="e2cc9-104">云设计模式</span><span class="sxs-lookup"><span data-stu-id="e2cc9-104">Cloud Design Patterns</span></span>

[!INCLUDE [header](../../_includes/header.md)]

<span data-ttu-id="e2cc9-105">这些设计模式可用于在云中构建可靠且可缩放的安全应用程序。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-105">These design patterns are useful for building reliable, scalable, secure applications in the cloud.</span></span>

<span data-ttu-id="e2cc9-106">每种模式描述了该模式解决的问题、有关应用该模式的注意事项，以及基于 Microsoft Azure 的示例。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-106">Each pattern describes the problem that the pattern addresses, considerations for applying the pattern, and an example based on Microsoft Azure.</span></span> <span data-ttu-id="e2cc9-107">大多数模式都包含了代码示例或代码片段，演示如何在 Azure 中实现该模式。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-107">Most of the patterns include code samples or snippets that show how to implement the pattern on Azure.</span></span> <span data-ttu-id="e2cc9-108">但是，无论托管在 Azure 还是其他云平台中，大多数模式都与任一分布式系统相关。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-108">However, most of the patterns are relevant to any distributed system, whether hosted on Azure or on other cloud platforms.</span></span>

## <a name="problem-areas-in-the-cloud"></a><span data-ttu-id="e2cc9-109">云中的问题区域</span><span class="sxs-lookup"><span data-stu-id="e2cc9-109">Problem areas in the cloud</span></span>

<ul id="categories" class="panel">
<span data-ttu-id="e2cc9-110">{%- for category in categories %}</span><span class="sxs-lookup"><span data-stu-id="e2cc9-110">{%- for category in categories %}</span></span>
    <li>
    <span data-ttu-id="e2cc9-111">{% include 'pattern-category-card' %}</span><span class="sxs-lookup"><span data-stu-id="e2cc9-111">{% include 'pattern-category-card' %}</span></span>
    </li>
<span data-ttu-id="e2cc9-112">{%- endfor %}</span><span class="sxs-lookup"><span data-stu-id="e2cc9-112">{%- endfor %}</span></span>
</ul>

## <a name="catalog-of-patterns"></a><span data-ttu-id="e2cc9-113">模式目录</span><span class="sxs-lookup"><span data-stu-id="e2cc9-113">Catalog of patterns</span></span>

| <span data-ttu-id="e2cc9-114">模式</span><span class="sxs-lookup"><span data-stu-id="e2cc9-114">Pattern</span></span> | <span data-ttu-id="e2cc9-115">摘要</span><span class="sxs-lookup"><span data-stu-id="e2cc9-115">Summary</span></span> |
| ------- | ------- |
<span data-ttu-id="e2cc9-116">{%- for pattern in patterns %} | [{{ pattern.title }}](./{{ pattern.file }}) | {{ pattern.description }} | {%- endfor %}</span><span class="sxs-lookup"><span data-stu-id="e2cc9-116">{%- for pattern in patterns %} | [{{ pattern.title }}](./{{ pattern.file }}) | {{ pattern.description }} | {%- endfor %}</span></span>