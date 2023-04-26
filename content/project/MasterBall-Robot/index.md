---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MasterBall | 大师球双形态机器人"
summary: "MasterBall "
authors: [周一唱]
tags: [机器人]
categories: []
date: 2023-04-25T16:32:43+08:00


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## 研究背景

随着智能机器人行业的快速发展，地面作业对机器人的依赖也越来越高。面对实际情况中的复杂地形，球-腿双形态机器人兼具球形机器人快速运动和多足机器人高避障能力的特点，具有更强的适应能力，是突破当前单形态机器人作业局限的重要发展方向。

## 产品概述

本产品为一种具有不同形态的智能机器人系统，本产品特殊的腿部结构使其可以实现在球形机器人和六足机器人之间进行形态切换，以满足面向复杂环境进行探测作业的要求。同时其灵活的结构设计和开放的系统设置不仅能更好地满足用户的个性化需求，还降低了用户二次开发的门槛，为进一步发展提供了更广阔的可能性。

## 产品设计

本产品由特殊设计结构的下位机、拥有对应遥控能力的上位机系统组成， 同时为其编写了适用于多种运动形态的智能算法。

![](http://sol.dlut.everains.com/wp-content/uploads/2022/08/image-4.png)

按照设计规划，下位机有着为多形态变换而设计的腿部结构，整体将满足以下几点需求：机器人结构坚固耐用，具有一定的抗冲击能力；运动结构之间配合良好，在变形及运动过程中不发生结构干涉；同时内部留有足够的空间搭载摄像头等传感器。

开发的上位机将能显示机器人的实时状态（包含所处形态、运动速度、平台位姿、位置、剩余电量等信息）；能远程对机器人的动作进行操作；可以接收摄像头、激光雷达等用于探测的传感器返回的画面信息，并封装图像识别功能。

![](http://sol.dlut.everains.com/wp-content/uploads/2022/08/image-5.png)

智能算法的研究内容包括：统合机器人的多种运动形态；使机器人具有通过传感器回传的数据判断周围环境，并自动切换形态的能力；具有在划定巡航区域

后，自主规划巡航路径的能力；具有能根据剩余电量自主判断巡航返程时间的能力。

## 产品核心创新

结构上，本产品为双形态机器人，可以在球形态与足式形态之间自由切换以满足不同情况的需求。球形态适合在平坦路面及上下坡路面行驶；足式形态适合在崎岖复杂的地形下行驶，并且在足式形态下，本产品还具有一定的负载和运载能力。独特的球形结构设计，能让本产品在受到外部冲击时能分散应力分布，使产品结构坚固稳定，具有一定的抗冲击能力。

功能上，本产品可自由搭配多种传感器，以满足不同场景的需求。双形态结构自由切换可以灵活应对复杂路况，搭载摄像头，红外成像仪，气体传感器，土壤湿度传感器等设备，可以进行野外环境探测以及搜救任务。搭载摄像头，心率传感器等，可以用作居家陪护，方便用户对家里老人和小孩的监护。

本产品留有扩展接口，方便用户进行二次开发，并满足用户个性化定制需求。本产品系统有着较高的开放度，降低了用户二次开发门槛。且本产品的灵活结构决定了其拥有较为广阔的二次开发前景，如多个球-腿符合机器人的协同作业、地面多形态机器人和无人机的协同作业等，将发挥一加一大于二的效果。
