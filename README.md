# rm-prettier
### Description:
This is tiny bash script to remove prettier packages and configuration options from a newly created NestJS project.  It attempts to cleanly remove the configuration options from the `.eslintrc.js` file.  

The current script is dependent on the format of this file at the time of writting.  If the folks at NestJS add/alter extends array, this script will need to be modified to match.

This script also optionally adds an indent rule for using tabs.  Just comment out or remove that line if you do not want it.

#### Requirements:
If you're in a bash shell and you're already creating a NestJS project, then you should already have everything you need.

**Useage:**

Run the script in the root of the NestJS project.  There are currently no arguments.
