# WAZUH SIEM

![Wazuh Loading Page](src/wazuh_logo.png)

## Introduction to Wazuh Retention Policy Through Index Lifecycle Management (ILM)

Index Lifecycle Management helps improve the performance of a Wazuh indexer cluster by managing the different stages of an index's lifecycle. It enables scheduled actions like index rollovers and deletions. These tasks are defined and automated using Index State Management (ISM) policies.

With ISM, you can automate index-related operations based on specific criteria such as the age, size, or document count of an index. This allows you to apply data lifecycle rules, including retention policies, without manual intervention.

This section outlines various configuration options available to optimize Wazuh indexer storage through effective index lifecycle management.

## Index Retention

Security regulations often require data to be stored and accessible for a set period to support audits and investigations. After this period, older data can usually be deleted to save storage.

To manage this automatically, you can create index retention policies that define how long data is kept and when it should be removed. These policies can also support index rollover, which helps manage index size and performance by creating new indexes based on age, size, or document count.

Together, retention and rollover policies ensure compliance, optimize storage, and maintain system performance.

## How To Implement Wazuh Retention Policy through ILM

* [Wazuh Retention Policy](wazuh_retention_policy.md)
* [Hot-Warm Architecture](hot_warm_architecture.md)

## Need Help To Deploy Wazuh? Reach me here

  * [Deploy Wazuh For Me](https://www.fiverr.com/packlah/install-wazuh-siem-for-you?context_referrer=tailored_homepage_perseus&source=recently_viewed_gigs&ref_ctx_id=e68c8431b0214894a1726eb5d672a5d6&context=recommendation&pckg_id=1&pos=1&context_alg=recently_viewed&seller_online=true&imp_id=55407c12-acb7-480d-9ad6-3d480322d433) 