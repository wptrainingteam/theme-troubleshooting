# Theme Troubleshooting

## Description

In this module you’ll learn about the basic troubleshooting steps that can be taken when something goes wrong with your WordPress theme.  The lesson will focus on troubleshooting an existing install of WordPress when activating, changing, or updating a theme.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic knowledge of [installing and activating WordPress themes](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-a-theme/) and [plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/)
*   Knowledge of how to back up [a WordPress database and files](https://make.wordpress.org/training/handbook/user-lessons/backing-up-your-wordpress-site/)
*   Knowledge of [basic troubleshooting](https://make.wordpress.org/training/handbook/user-lessons/troubleshooting-basics/).
*   Knowledge of how to [update WordPress core, themes, and plugins](https://make.wordpress.org/training/handbook/user-lessons/managing-updates/)

## Objectives

*   Students will be able to identify and eliminate variables when troubleshooting problems with their theme.
*   Students will be able be specific when stating the problem in support forums.
*   Students will be confident in solving problems.

## Assets

*   A local install running [WordPress version 4.7](https://wordpress.org/download/release-archive/)

## Screening Questions

*   Are you familiar with installing and activating themes and plugins via the WordPress dashboard?

## Teacher Notes

*   It is ideal to pair this lesson with the Backing up Your WordPress Site lesson plan so that students learn how to back up their WordPress site before running updates.
*   It is ideal to pair this lesson with the Basic Troubleshooting lesson plan so that students learn the basic concepts for identifying and eliminating variables.
*   This lesson uses WordPress version 4.7 on a local installation for demonstration purposes. Older versions of WordPress should never be used on production websites.
*   Encourage students to be confident in defining and solving problems.
*   Empower students to use Google strategically using site: searches as described under [Search First on Using the Support Forums](https://codex.wordpress.org/Using_the_Support_Forums#Search_First).
*   Remind students that theme developers are people too and to be polite and courteous when requesting support.

## Troubleshooting themes

### Problems installing or activating a theme

Check to make sure the theme you installed is the active theme. Go to the Admin Dashboard and click on Appearance > Themes. ![](https://make.wordpress.org/training/files/2014/10/theme-active.png) If the theme you want to use is not active, hover over the theme thumbnail and click the Activate button. If you see an error message after attempting to activate a theme:

*   Follow the steps in [Troubleshooting Basics](https://make.wordpress.org/training/handbook/user-lessons/troubleshooting-basics/) to see if the error goes away.
*   If the error persists, contact the theme developer with the specific error message. See _Getting support_ below.

If you purchased a commercial theme, read the documentation that comes with the theme for specific instructions for installing the theme. Common issues with installing commercial themes include:

*   **Theme zip file is too large for you to upload via Themes > Add New > Upload.** You will need to contact your web host to increase the maximum file upload size on your hosting account.
*   **Wrong file is uploaded.** Commercial themes often include many other assets in their download files, and you may inadvertently upload the entire download rather than just the theme.
*   **Commercial themes often come with parent and child theme.** Both the parent and child theme need to be installed, but only the child theme is activated.

### Issues after updating a theme

Before updating a theme, it is best practice to make a backup of the site. Better yet, it is best practice to test the update in a staging site or other development area first before applying the update to the live site. **1 – Read the documentation and support forums** Other people may be experiencing the same problem. Log in to the WordPress or theme-specific forum and use the search feature to search on the problem you are having. Chances are the developers are aware of the issue and are working on a solution or have an update or fix you can immediately apply. Be sure to [read the documentation](https://make.wordpress.org/training/?post_type=handbook&p=1581) for the theme to learn about changes made to the theme. **2 – Re-save options and use correct shortcodes**

*   If a slider or other plugin feature does not load properly after updating, you may need to click Save Changes or Update in the slider, theme, or plugin interface to re-connect your settings.
*   Compare images and theme settings to your old version. Major updates to a theme may result in your needing to re-select all your options.
*   Some plugin or theme shortcodes may have changed, so you need to read the documentation and use the correct shortcodes.

**3 – Clear your site cache and browser cache** Your site might look broken after an update. Cached files in your browser may interfere with the proper loading of the site. To clear various caches:

*   Login to your WordPress Dashboard and delete any cached files in your caching plugin.
*   Login to your web hosting control panel and check for any server-level cache features and clear the cache.
*   Delete all the cached files in your browser.
*   Try viewing the site from or logging in via a different browser.

**4 – Preserve changes made to theme** If you modified any of the theme files, these changes will be overwritten when you update the theme. Best practice is to use a [child theme](https://make.wordpress.org/training/handbook/theme-school/child-themes/) so updates to the parent theme do not overwrite your changes.

### Problems after changing themes

Not all themes have the same features. Theme-specific features include:

*   Widget areas
*   Image sliders and galleries
*   Unique layouts
*   Headers and footers
*   Background
*   Styling options
*   Menu locations

The main content of your posts and pages will not change or be deleted when you change themes. This is the beauty of using a Content Management System. The design and content are separate. However, some themes have unique layouts, shortcodes, and other features that will not be available when you change themes. When changing themes, you may need to:

*   Re-create custom layouts using the new theme's unique options.
*   Use the [Theme Customizer](https://make.wordpress.org/training/handbook/user-lessons/theme-customizer/) to re-select your styles, fonts, options, widgets, and menus.
*   Clear your browser, WordPress, and hosting cache to see the changes.

### Getting support

To get support for themes from WordPress.org, find the theme in the Themes area of WordPress.org. Click the **View support forum** button in the right sidebar of the theme page. Look through the recent topics posted to see if any apply to you. You may find that someone else is having the same problem, and a solution has already been posted. ![](https://make.wordpress.org/training/files/2014/10/themes-support-forum.png) Before posting to the forums, be sure to read [Using the Support Forums](https://codex.wordpress.org/Using_the_Support_Forums).

## Exercises

*   Have students change themes and note how the new theme changes the look of their site and what options need to be selected to work with the new theme.
*   Have students login to WordPress.org, find their theme on WordPress.org and view the support forums for the theme.
*   Have students use Google to search WordPress.org for issues related to their theme. See example Google searches on [Using the Support Forums](https://codex.wordpress.org/Using_the_Support_Forums#Search_First).

## Quiz

**Write out the question.**

1.  Where is the best place to find support for your WordPress.org theme?
2.  Why do you need to back up your site before updating your theme?
3.  What things on the site might change if you change themes?
4.  What is best way to describe your issue on the support forums?
5.  What should you always do after updating or changing a theme?

**Answer:**

1.  In the Support Forums.
2.  Update may result in the look of the site changing or changes made to files being lost.
3.  Menus, styling, custom layouts, and widget areas.
4.  Use descriptive title, be specific in describing the problem, include version numbers, be courteous, provide details for replicating the problem.
5.  Clear your hosting, plugin, and browser cache.
