---
title: "Scheduling runs with monitors"
order: 56.1
updated: 2021-02-16
page_id: "scheduling_collection_runs_with_monitors"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Using the Collection Runner"
    url: "/docs/running-collections/intro-to-collection-runs/"
  - type: section
    name: "Additional resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "API Monitoring | The Exploratory"
    url: "https://youtu.be/tDQzY1Hn2LY"
  - type: dynamic_blog
    name: "Blog Posts"
    blog_tag: "monitors"

warning: false
---

You can automate [collection runs](/docs/running-collections/intro-to-collection-runs/) using [monitors](/docs/monitoring-your-api/intro-monitors/) to schedule runs and receive reports on your request test results.

To add or access monitors for a particular collection, select __Monitors__ in the sidebar.

<img alt="Monitors v8" src="https://assets.postman.com/postman-docs/create-a-monitor-v8.jpg" height="400px"/>

Any monitors already attached to your collection will appear. Select __Create a monitor__ to add one (or __+ Create a new Monitor__ if you already have one on the collection).

You can also add a monitor from a collection. Select the collection you want to add a monitor to, then select the more actions icon <img alt="More actions icon" src="https://assets.postman.com/postman-docs/icon-more-actions-v9.jpg#icon" width="16px"> > __Monitor collection__.

Give your monitor a name, select a collection to use, choose a version tag, and an optional environment for your scheduled collection runs to reference. Enter the frequency you want your monitor to run on, and select a region. Select __Create__ and your monitor will run on the schedule you entered.

[![Add new monitor to collection](https://assets.postman.com/postman-docs/create-new-monitor-overview-v8.jpg)](https://assets.postman.com/postman-docs/create-new-monitor-overview-v8.jpg)

Your new monitor will appear in the monitor overview. You can open the monitor overview tab to [view your monitor results](/docs/monitoring-your-api/viewing-monitor-results/) at any time.

<img alt ="New monitor created" src="https://assets.postman.com/postman-docs/new-monitor-created-v8.jpg" height ="400px"/>
