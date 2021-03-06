# Partial.ly-Widget-with-JavaScript-and-Squarespace

<h3>Function & Description:</h3>
This is a widget + button thingy I customised with some bits of JavaScript code for a client. They specialise in making attention-grabbing packages/boxes that help their clients drive sales. This widget + button from partial.ly allows their clients pay for this service installmentally.  

<h3>Challenge faced:</h3>
The widget would not show up on the landing page, no matter what the client tried. So, I had to log in from my end to fix it. I also could not get the button to display at first.


<h3>Solution:</h3>
I finally found a way to make the button display on the same side as the widget with the following code:

```
<div id="partiallyWidget"></div>
<script>
document.partiallyWidgetConfig = {
  offer: 'dae8e913-de70-4618-aa0d-5aae37e5e75c',
  amount: 99.99,
  includeCheckout: true;
  targetSelector: '#partiallyWidget'
};

(function() {
    var script = document.createElement('script');
    script.type = 'text/javascript';
    script.src = 'https://partial.ly/js/partially-widget.js';
    script.async = true;
    document.head.appendChild(script);
})();
</script>
```

<h3>Technology Used:</h3>

- JavaScript
- Partial.ly
- Squarespace 
- Github

<h3>Link to site:</h3>
https://unpopd.com/

<h3>Screenshots:</h3>

![Unpopd 1](https://user-images.githubusercontent.com/40691059/77821333-c4d1dc00-70e9-11ea-9831-cfd5a51f92c5.PNG)

![Unpopd2](https://user-images.githubusercontent.com/40691059/77821335-c8656300-70e9-11ea-90bc-389e88aa96fb.PNG)



