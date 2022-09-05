# Digital Clock 

Question (easy)

Digital Clock

Implementation Details:

• Create a Digital Clock with React.

• When Digital Clock is mounted, the Digital Clock should update the state variable time with the current time.

• This Digital Clock should update the time variable regularly at an interval of 1 sec.

• When the component is unmounted then Digital Clock should be terminated to free up resources.


Acceptance Criteria

Date time should be displayed inside div with classname "date-time"

Use JavaScript class Date.

Update Digital Clock in every second.

Terminate Digital Clock on unmounting.


Time Format

use toLocaleString method on date object to display date-time


It should be displayed like this: - "12/2/2021, 3:17:23 PM" (without double quotes)

On some OS/browsers , toLocaleString may or may not show AM/PM at the end, but the solution will still be acceptable
