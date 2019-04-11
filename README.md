# D365JS 
Fast , clean and reusable client side library for MS Dynamics 365 .`Beta v1.0.0.0`

## Installation
**Step 1** : Simply add D365JS to your entity form like the way we do for custom script file.
[![](https://static.wixstatic.com/media/b59c13_a698a23ab6e243d487128e06644c1fe1~mv2.jpg/v1/fill/w_615,h_508,al_c,q_80,usm_0.66_1.00_0.01/PreRequisites.webp)](https://static.wixstatic.com/media/b59c13_a698a23ab6e243d487128e06644c1fe1~mv2.jpg/v1/fill/w_615,h_508,al_c,q_80,usm_0.66_1.00_0.01/PreRequisites.webp)

**Step 2** : To initiate D365JS in your CRM entity, just call the iStart method on the very first position of your entity Form onLoad event and check "Pass execution context as first parmeter".
[![](https://static.wixstatic.com/media/b59c13_493036d5d52544148dda07ad31a0ce2a~mv2.jpg/v1/fill/w_615,h_289,al_c,lg_1,q_80/iStart.webp)](https://static.wixstatic.com/media/b59c13_493036d5d52544148dda07ad31a0ce2a~mv2.jpg/v1/fill/w_615,h_289,al_c,lg_1,q_80/iStart.webp)

Wow ! with just a minor configuration, D365JS is ready to be utilized in your custom js libraray. 

## Why ?
After v9.0 update of MS Dynamics 365 online, the way of doing clinet side operations has been completely changed like passing execution context for all form events, replacement of synchronus REST calls by XRM.Web Api etc.
Following are the reason says why you should use D365JS in your CRM instance ?
1. No need to pass execution context and and save formcontext in your custom js for individual methods
2. Resuable , easy to modify and very less size.
3. Optimised and Fast
4. Additional Features to speedup the development by neglecting traditional way of writing codes.
5. Follows all v9.0 recommendations inherently and provides you the rich development feel.
6. Up to date with all latest releases in MS client side architecutre. (current ver 9.0). 
7. No need of exception handling. D365JS is smart enough to handle all run time exceptions without stopping other operations.

## What and How ?
D365JS is a first of its kind client side script for MS Dynamics built upon the latest recommnedation from microsoft for MS Dynamics 365 v9.0 updates . D365JS consists of four components that gives you full flexibility to do all client side operatinons in your entity form. 
<table>
  <tr>
    <td>iForm</td>
    <td>To do Attributes,controls,sections,tabs and other Form related operations</td>
  </tr>
  <tr>
    <td>iUser</td>
    <td>To do User and Instance related operations</td>
  </tr>
    <tr>
    <td>iData</td>
    <td>To perform CRUD operation from Client Side using inbuilt Data methods</td>
  </tr>
  <tr>
    <td>iMedia</td>
    <td>To do media options like capture audio , video upload of any file into CRM </td>
  </tr>
</table>
