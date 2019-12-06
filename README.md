Reorganized React Code

Created a new component AddFolder that implemented a form to capture the name of a new folder from the user. 
This form submits the name of the new folder to the POST /folders endpoint on the server. 
Errors have been handled and button to the navigation invokes the new form.
Created a new component AddNote too that implements a form to capture the name, content and folder for a new Note. Submitted to the POST /notes endpoint on the server. 
Added validation to ensure that the name of the note is not left blank. 
The folder has been selected from a list of existing folders. Errors have been handled and a a button to the note list page invokes this new form.
The error boundary component also has been handled and has this component has been added to specific points in the component structure.
Components that receives props from its parent have been refactored to define PropType validation too. 
