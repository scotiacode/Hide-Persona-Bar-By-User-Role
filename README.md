# Hide Persona Bar By User Role

Hide the Persona Bar (Admin Control Panel UX) from content editors and other users in DNN Platform. 

Simply install into your DNN Platform v9.0.0+ website and assign the 'Hide Persona Bar' role to any user. The next time the user try's to access a page the Persona Bar will be automatically hidden from them.

Use this to help create simple editing experiences for your users when a full control panel experience is not needed in your use case. 

Note(s): 

1. This does not work for Super User / Host accounts, they will always have access to the Persona Bar UI.

2. You can accidently hide the Persona Bar from yourself if you are an Administrator and apply the role to your account. If this happens you will need to remove the role from your user manually in the database of your website or another programatic means.

3. User's that have access editing access permissions will still have access to the same API's, etc. that they would have before applying the 'Hide Persona Bar' role.
