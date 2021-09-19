# discord-custom-css
Custom css for Discord

# How to apply?
- Open console by pressing `ctrl+shift+i`
- Copy **[inject-script.js](https://github.com/DevAndromeda/discord-custom-css/blob/main/inject-script.js)**
- Paste it in console

# is it against tos?
idk, maybe? This process does not involve the use of clients like BetterDiscord or Powercord so this should be much safer.

# is it dangerous?
The script just injects the css to `<head>` element and nothing else.

# why did it disappear on restart?
This css injection is not permanent, so you would need to do this every time you load discord

# does this work in browsers?
Yes!

# is it BetterDiscord?
No.

# Script

```js
document.querySelector("head").innerHTML += `<style>@import url(https://fonts.googleapis.com/css2?family=Poppins&display=swap);:root{--blurple:#5865F2;--blurple-hover:#3c47c4}.theme-dark{--background-primary:#23272A;--background-secondary:#1a1e21;--background-secondary-alt:#15181b;--background-tertiary:#111416;--channeltextarea-background:#1a1e21;--background-floating:#111416;--scrollbar-auto-thumb:#0000004a;--scrollbar-auto-track:#00000036;--background-modifier-accent:hsla(0, 0%, 100%, 0.03)}.layer-3QrUeG[aria-label=CHANNEL_SETTINGS] .contentRegion-3nDuYy,.layer-3QrUeG[aria-label=CHANNEL_SETTINGS] .standardSidebarView-3F1I7i,.layer-3QrUeG[aria-label=GUILD_SETTINGS] .contentRegion-3nDuYy,.layer-3QrUeG[aria-label=GUILD_SETTINGS] .standardSidebarView-3F1I7i,.layer-3QrUeG[aria-label=USER_SETTINGS] .contentRegion-3nDuYy,.layer-3QrUeG[aria-label=USER_SETTINGS] .standardSidebarView-3F1I7i{background-color:var(--background-tertiary)}.actionButtons-14eAc_>:last-child{position:relative;right:9px}.menu-3sdvDG{border-radius:10px!important}.chatHeaderBar-4vZS1x{margin:15px;border-radius:10px!important}.sidebar-2K8pFh{margin-bottom:15px;margin-top:15px;border-radius:10px!important}.notice-3bPHh-{margin-top:15px;margin-right:15px;border-radius:10px!important}.members-1998pB,.panels-j1Uci_{margin:15px;border-radius:10px!important}.chat-3bRxxu,.container-1D34oG,.pageWrapper-1PgVDX{margin:15px;border-radius:10px!important}.notice-3uyY6c{margin-top:15px;margin-right:15px}.threadSidebar-1o3BTy{margin-right:15px;margin-top:15px;margin-bottom:15px;margin-left:0}.sidebarRegion-VFTUkN{margin-top:15px;margin-bottom:15px;margin-left:15px}.channelTextArea-2VhZ6z .scrollableContainer-2NUZem,.container-2Pjhx-,.container-2Pjhx-:hover,.content-1x5b-n,.content-1x5b-n:hover,.contentRegionScroller-26nc1e,.contentWrapper-SvZHNd,.contentWrapper-SvZHNd .result-3w1ZcL,.input-2VB9rf,.messagesPopoutWrap-1MQ1bW,.notice-3uyY6c,.popout-103y-5,.quickswitcher-3JagVE,.result-oB0z--,.sidebarRegionScroller-3MXcoP,.threadSidebar-1o3BTy{border-radius:10px!important}.contentRegion-3nDuYy{border-radius:10px;margin-top:15px;margin-left:15px;margin-bottom:15px;margin-right:15px}.guilds-1SWlCJ{margin:15px;border-radius:10px!important}.scroller-1Bvpku{background:var(--background-secondary-alt)!important;padding-top:10px;padding-bottom:10px}.scroller-1Bvpku .tutorialContainer-2sGCg9{padding-top:10px}.role-2irmRk{border-radius:10px}.avatarPositionNormal-aZjAsn+.headerTop-3vNv-a{padding-top:70px!important}.avatarPositionNormal-aZjAsn{top:-45px!important}.userPopout-xaxa6l .banner-2QYc2d{position:absolute;width:calc(100% + 4px);height:calc(100% + 4px);top:-2px;left:-2px;background-size:calc(100% - 2px);background-position:center 2px;border-radius:10px}.userPopout-xaxa6l .banner-2QYc2d:after{content:"";display:block;background-color:inherit;border-top-left-radius:inherit;border-top-right-radius:inherit;width:100%;height:124px;clip-path:path("M 2 12 Q 2 2 12 2 L 292 2 Q 302 2 302 12 L 302 123 L 304 123 L 304 0 L 0 0 L 0 123 L 2 123 L 2 12")}.body-3HBlXn,.footer-3UKYOU,.headerTop-3vNv-a{background-color:var(--background-floating)!important}.avatarPositionNormal-aZjAsn{top:16px}.avatarPositionNormal-aZjAsn+.headerTop-3vNv-a{padding-top:119px}.avatarPositionPremium-3We5Ho+.headerTop-3vNv-a{margin-top:119px}.avatarPositionNormal-aZjAsn+.headerTop-3vNv-a>.profileBadges-ohc0Vu{top:75px}body,button{font-family:Poppins,sans-serif!important}.barFill-23-gu-{background:var(--blurple)}.lookFilled-1Gx00P.colorBrand-3pXr91{background-color:var(--blurple)}.lookFilled-1Gx00P.colorBrand-3pXr91:hover{background-color:var(--blurple-hover)}.name-1jkAdW,.title-29uC1r{font-size:18px!important}.membersGroup-v9BXpm{font-weight:700}.userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L .roleCircle-3xAZ1j::before{background:inherit}.pageWrapper-1PgVDX,.theme-dark .container-1D34oG{background-color:var(--background-primary)!important}.content-2M3n_H a{color:#fff!important}.markup-2BOw-j a{color:#959dfc}.connectedAccounts-repVzS{margin-top:0;justify-content:space-evenly}.theme-dark .connectedAccount-36nQx7{margin-top:5px;background-color:var(--background-modifier-accent)}.activity-fViXj7{padding:16px 16px 16px}.theme-dark .body-3iLsc4{background-color:#0e1113}.theme-dark .footer-1fjuF6{background-color:#0e1113}.theme-dark .lookFilled-1Gx00P.colorGrey-2DXtkV{background-color:#292d33}.theme-dark .lookFilled-1Gx00P.colorGrey-2DXtkV:hover{background-color:#2f343b}.setIdentityLink-OpBDR6{display:none}.customStatus-3NamXG .customStatusEmoji-1itGdP:not(:last-child){margin-right:4.8px}.theme-dark .uploadModal-2ifh8j{background-color:var(--background-primary)}.theme-dark .footer-3mqk7D{background-color:var(--background-secondary)}.theme-dark .hljs{background-color:#1a1e21}.messageAttachment-1aDidq{width:100%}.theme-dark .root-1gCeng{background-color:var(--background-primary)}.theme-dark .footer-2gL1pp{background-color:var(--background-secondary)}#GHOSTCOMMANDSDIVWRAPPER{background:linear-gradient(180deg,#1a1e21 65%,rgba(14,20,24,0) 10%)!important}.GHOSTCOMMANDLISTITEM{background-color:#23272a}.GHOSTCOMMANDLISTITEM:hover{background-color:#202427}.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9{background-color:#30363b}.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9:hover{background-color:#2c3236}</style>`
```

# Preview
![](https://i.imgur.com/MtI6WnG.png)
