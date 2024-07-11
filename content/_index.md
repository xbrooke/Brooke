=---
title: '首页'  # 页面标题
date: 2023-10-24  # 页面最后更新日期
type: landing  # 页面类型（这里是一个落地页）

design:
  spacing: "4rem"  # 默认的区块间距

# 注意：`username`指的是`content/authors/`目录下作者的文件夹名

# 页面各个部分
sections:
  - block: biography  # 个人简介部分
    content:
      username: 徐斌  # 作者用户名
      button:  # 可选的个人简介下的行动按钮
        text: 下载简历  # 按钮文本
        url: uploads/resume.pdf  # 简历文件的URL
    design:
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg  # 个人简介的横幅图片文件名
      biography:
        style: 'text-align: justify; font-size: 0.8em;'  # 个人简介文本的样式

  - block: experience  # 经验部分
    content:
      username: 徐斌  # 作者用户名
    design:
      date_format: 'January 2006'  # 经验条目中日期的格式
      is_education_first: false  # 是否先显示教育经历还是工作经历（这里先显示工作经历）

  - block: skills  # 技能部分
    content:
      title: 技能与爱好  # 标题
      username: 徐斌  # 作者用户名

  - block: languages  # 语言能力部分
    content:
      title: 语言能力  # 标题
      username: 徐斌  # 作者用户名
---
