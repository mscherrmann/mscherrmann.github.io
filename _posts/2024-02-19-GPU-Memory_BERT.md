---
layout: post
title: Understand GPU Memory Usage for Language Model Fine-Tuning
date: 2024-02-19 15:00:00+0100
description:
tags:
categories: Insights
giscus_comments: false
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/testGPUMemoryBertTraining.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/testGPUMemoryBertTraining.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
<a href="{{ '/assets/jupyter/testGPUMemoryBertTraining.ipynb' | relative_url }}" download class="download-button">Download Notebook</a>
{% jupyter_notebook jupyter_path %}
{% else %}
<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

<style>
.download-button {
    display: inline-block;
    padding: 5px 10px; /* Smaller padding */
    margin: 5px 0; /* Smaller margin */
    background-color: #2698BA;
    color: white;
    text-decoration: none;
    border-radius: 3px; /* Slightly rounded corners */
    text-align: center;
    font-size: 14px; /* Smaller font size */
}
</style>
