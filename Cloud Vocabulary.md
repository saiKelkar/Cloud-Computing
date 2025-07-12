**Virtual Machine** 
-- a digitized version of a physical computer
-- can run programs and operating systems, store data, connect to networks, and do other computing functions
-- uses entirely virtual resources instead of physical components

**Markdown**
-- lightweight markup language used to format plain text documents

**Gist** 
-- simple way to share code snippets and fragments with others using GitHub. 
```
import requests

url = "https://api.github.com/gists/gist_id"

response = requests.get(url)
print(response.json()["description"])

```

**Quarterly Plan**
-- project schedule mapped out week-by-week for an entire quarter to outline goals and plan development

**Ticket Tracking**
-- using a system to track progress on tasks and action items - enables visibility into status without excessive meetings

**Continuous Delivery**
-- software engineering practice to build, test, and release software rapidly, reliably, and sustainably
```
import ci_cd

pipeline = ci_cd.create_pipeline()

pipeline.build()
pipeline.test()
pipeline.deploy()

```

**Automated Testing**
-- run tests automatically without human input to verify software functionality and correctness

**Kaizen**
-- Japanese business philosophy focused on continuous improvement through gradual, incremental steps

**Makefile**
-- a recipe for building software
-- available on Linux systems
-- simplifies essential steps in a software project

**Tests**
-- ensures your software works
-- functional
-- integration
-- load testing 
-- save time

**Linting**
-- syntax
-- catches bugs before they happen
-- enhances automation

**Python Virtual Environment**
-- isolates Python to a directory
-- python3 -m venv ~/.your-project-env
-- source ~/.your-project-env/bin/activate
-- a best practice

**GitHub Actions**
-- SaaS
-- Continuous Integration (for automatic testing)
-- YAML based (Yet Another Markup Language -- human-readable structured data format commonly used for configuration files)

**Build Server**
-- server that automatically runs builds and tests whenever code changes are pushed to a repo
-- GitHub Actions is an example of a popular cloud-based build server

**Artifact** 
-- output of a build process, usually some file(s) that get deployed or released if tests pass
-- represent the state of the code at a point in time





