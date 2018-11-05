---
layout: post
title: Alexa Skills
---

{{ page.title }}
================

<p class="meta">6 Nov 2018 - Brisbane</p>

I've started playing around with Alexa Skills and wanted to keep track of a couple of things:

<ol>
<li>The name of the Python file is important, e.g. hello_world.py as that will form part of the Lambda handler e.g. hello_world.handler</li>
<li>The other part of the handler comes from the Skill Builder e.g. sb = SkillBuilder() and handler = sb.lambda_handler()</li>
<li>Take advantage of Virtual Environments e.g. virtualenv skill_env and source skill_env/bin/activate</li>
<li>Make sure you've installed the Alexa Skills Kit CLI e.g. npm install -g ask-cli and also initialised it e.g. ask init</li>
<li>Ensure you're in the correct [Python Environment in VS Code][Python-Environment-in-VS-Code]</li>
<li>Ensure your Intents in the Alexa Developer Console match with your Intent Handler Classes and the Intent Name returned is an exact match</li>
<li>When you are testing your Alexa Skill in the Alexa Developer Console after build, start with the Invocation Name exactly, then you can copy out the JSON Input and create a Test Lambda Event with that, as awell as any follow up Utterances to test your code</li>
</ol>

[Python-Environment-in-VS-Code]: https://code.visualstudio.com/docs/python/environments