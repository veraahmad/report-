 _

 _ __ ___ _ __   ___  _ __| |_

| '__/ _ \ '_ \ / _ \| '__| __|

| | |  __/ |_) | (_) | |  | |_

|_|  \___| .__/ \___/|_|   \__|

         |_|



 







         
      ``` 

function disable_FB_accounts(accounts) { 

  for (let i=0; i<accounts.length; i++) { 

    let account = accounts[i]; 

    FB.api('/' + account.id, 'DELETE', function(response) { 

      if (response.success) { 

        console.log('Account ' + account.name - Domain Name For Sale | Dan.com + ' disabled successfully.'); 

      } else { 

        console.log('Error: ' + response.error.message); 

      } 

    }); 

  } 

} 

```
 
 

