---
title: 'Managing your GitHub Copilot Business subscription'
intro: 'Set up {% data variables.product.prodname_copilot_for_business %} for your organization{% ifversion ghec %} or enterprise{% endif %} account and manage your subscription.'
redirect_from:
  - /billing/managing-billing-for-github-copilot/managing-your-github-copilot-subscription-for-your-organization-or-enterprise
product: '{% data reusables.gated-features.copilot-billing %}'
versions:
  feature: copilot
type: how_to
topics:
  - Copilot
shortTitle: Your business subscription
---

{% note %}

**Note:** If you are a member of your organization{% ifversion ghec %} or enterprise{% endif %}, and you want to set up a {% data variables.product.prodname_copilot_for_business %} subscription, you will need to contact your organization{% ifversion ghec %} or enterprise{% endif %} administrator.

{% endnote %}

## About managing your {% data variables.product.prodname_copilot_for_business %} subscription

This article applies to setting up and managing a {% data variables.product.prodname_copilot %} subscription for your organization{% ifversion ghec %} or enterprise{% endif %} account. If you want to set up {% data variables.product.prodname_copilot %} for your personal account, see "[AUTOTITLE](/billing/managing-billing-for-github-copilot/managing-your-github-copilot-subscription-for-your-personal-account)." If you want to benefit from {% data variables.product.prodname_copilot %} features in {% data variables.product.prodname_dotcom_the_website %}, you can set up a subscription to {% data variables.product.prodname_copilot_enterprise %}. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/billing/managing-billing-for-github-copilot/managing-your-github-copilot-enterprise-subscription){% ifversion fpt %}" in the {% data variables.product.prodname_ghe_cloud %} documentation.{% else %}."{% endif %}

{% ifversion ghec %}

You can set up a {% data variables.product.prodname_copilot_business_short %} subscription for your organization or enterprise account. If you set up a subscription for your organization account, you can grant access to {% data variables.product.prodname_copilot %} for individuals and teams within your organization. If you set up a subscription for your enterprise account, you can grant access to {% data variables.product.prodname_copilot %} for organizations within your enterprise.

{% endif %}

{% data reusables.billing.billing-info %}

{% ifversion ghec %}

## Setting up a {% data variables.product.prodname_copilot_business_short %} subscription for your enterprise

Before you can start using {% data variables.product.prodname_copilot_business_short %} in your enterprise, you will need to set up a subscription.

### Customers under a Microsoft Enterprise Agreement

{% data reusables.copilot.signup-procedure-enterprise-msft-ea %}

### Customers under a direct GitHub contract

{% data reusables.copilot.signup-procedure-enterprise %}

{% endif %}

{% ifversion fpt %}

## Setting up a {% data variables.product.prodname_copilot_business_short %} subscription for your organization

Before you can start using {% data variables.product.prodname_copilot %} in your organization account, you will need to set up a subscription.

{% data reusables.copilot.signup-procedure-org %}

{% endif %}

## Modifying your {% data variables.product.prodname_copilot_business_short %} subscription

{% ifversion ghec %}

You can modify your {% data variables.product.prodname_copilot_business_short %} subscription for your organization or for your enterprise account.

### Modifying your {% data variables.product.prodname_copilot_business_short %} settings for your enterprise

{% note %}

**Note:** Only enterprise owners can modify policies for {% data variables.product.prodname_copilot %}.

{% endnote %}

You can modify the policies for the use of {% data variables.product.prodname_copilot %} suggestions that match public code in your enterprise, and the access to your {% data variables.product.prodname_copilot %} subscription. For more information, see "[AUTOTITLE](/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-github-copilot-in-your-enterprise)."

### Modifying your {% data variables.product.prodname_copilot_business_short %} settings for your organization

{% endif %}
You can configure {% data variables.product.prodname_copilot %} in your organization, including granting and revoking access to individuals and teams, and determining whether to block suggestions that match public code. For more information, see "[AUTOTITLE](/copilot/configuring-github-copilot/configuring-github-copilot-settings-in-your-organization)."

## Canceling your {% data variables.product.prodname_copilot_business_short %} subscription

{% ifversion ghec %}

You can either disable {% data variables.product.prodname_copilot %} for all organizations in your enterprise or for a specific organization.

### Canceling your {% data variables.product.prodname_copilot_business_short %} subscription for your enterprise account

{% note %}

**Note:** You must be an enterprise owner to disable {% data variables.product.prodname_copilot_business_short %} for all organizations in your enterprise.

{% endnote %}

{% data reusables.copilot.disable-copilot-for-all-orgs %}

### Canceling your {% data variables.product.prodname_copilot_business_short %} subscription for your organization account {% endif %}

To cancel your {% data variables.product.prodname_copilot_business_short %} subscription for your organization account, you need to remove all assigned {% data variables.product.prodname_copilot %} seats.

{% data reusables.copilot.disable-copilot-organization %}

## Further reading

- "[AUTOTITLE](/copilot/overview-of-github-copilot/about-github-copilot-business)"
- "[AUTOTITLE](/copilot/managing-copilot-business/enabling-and-setting-up-github-copilot-business)"
