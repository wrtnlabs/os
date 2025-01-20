# Product Main Repository

This repository serves as a central hub for bug reporting of the product.

1. [Product Bug Reports](#-bug-reports)
2. [How to manage Issue](#how-to-manage-issue)

   
## 🐞 Bug Reports

### How to Report a Bug

1. Click the "New Issue" button in the [Issues tab](../../issues)
2. Select the "Bug Report" template
3. Please provide the following information in detail:
   - Environment (OS, Browser version, etc.)
   - Steps to reproduce the bug
   - Expected behavior vs Actual behavior
   - Screenshots or videos (if possible)
4. Add appropriate label:
   - `Bug`: For technical issues and malfunctions
   - `Request For Change UI`: For UI-related changes and improvements
5. Add Project  
   If this error is about current sprint, you can assgin current sprint  
   of course, you should add proejct `Ecosystem 2.0`  
   
### Bug Resolution Process

1. Create an initial issue in this main repository
2. Through discussion in the issue, identify the bug location and assign responsible team members
3. Create derivative issues in relevant repositories and link them to the main issue
   - This ensures all stakeholders can track the issue's progress in the main repository
   - Prevents visibility issues that would occur if issues were directly created in individual repositories
4. Issues are closed progressively after resolution

## How to manage Issue

1. All the issue should regist Github Project
   - **required** : `start_date`, `end_date` (if not started issue, you can omit this)
   - **required** : when `project` can be specified, you should regist `project` for task tracking
  
2. All the meatadata about progress and exception should record target issue  
   Only this, Even first-timers can easily participate in the context.

3. If target issue not contains current sprint, you can omit sprint property
