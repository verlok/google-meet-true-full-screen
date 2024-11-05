# Google Meet _true_ Full Screen

A bookmarklet for toggling real full screen on Google Meet

## How to use:

- Create a new bookmark named "GM full" in your bookmark bar. No mater what it points to for now.
- Edit the bookmark link, and replace it with 
  ```js
  javascript:const jsCtrlId = 'hVZhab'; for (const controller of document.querySelectorAll(`[jscontroller="${jsCtrlId}"]`)) if (controller.style.display === '') controller.style.display = 'none'; else controller.style.display = '';
  ```
- Click on the bookmark while a Google Meet meeting is in place, and it will hide all controls
- Click it again to make the controls visible again
