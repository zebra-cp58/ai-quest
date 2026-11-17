# 📖 AI Quest
AI Quest: A WeChat mini-program supporting knowledge tests and document uploads for self-assessment.

> ⚠️ 声明：本项目为学习二次开发项目，原始代码来自：https://github.com/liyupi/yu-ai-learn.git，在原有基础上进行功能改造、学习调试。

## ✨ 项目简介
本项目基于 **Taro（微信小程序） + Python FastAPI + LangChain** 开发，前后端分离架构，整合主流小程序开发与AI应用开发技术。

当前版本已实现基础闯关答题能力，支持单选、多选、判断题型；作答后即时高亮正确答案、标记错误选项，无论答对答错，均提供题目解析与配套知识点。

题目输入自由灵活，可自主选择学习内容；项目可直接在微信开发者工具模拟器中运行调试。

后续规划：接入RAG私有知识库，支持上传自有文档自动出题；新增AI题目配图生成等功能。

## ✨ Introduction
> Note: This is a learning and secondary development project. The original code is from: https://github.com/liyupi/yu-ai-learn.git. Feature reconstruction and debugging are implemented on the basis of the original project.

This project adopts a front-end and back-end separated architecture built with **Taro (WeChat Mini Program) + Python FastAPI + LangChain**, integrating mainstream mini-program and AI application development technologies.

The current version supports basic quiz challenge functions, including single-choice, multiple-choice and true/false questions. After submission, correct answers will be highlighted and wrong options marked immediately. Explanations and related knowledge points will be provided whether your answer is right or wrong.

You can freely define topics for learning. The project can run and debug directly in the WeChat Developer Tools simulator.

Roadmap: Add RAG-based private knowledge base to generate quizzes from custom documents; support AI image generation for quiz illustrations, etc.
