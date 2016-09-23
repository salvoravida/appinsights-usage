# appinsights-usage

### Javascript module to track usage with [Application Insights](https://github.com/Microsoft/ApplicationInsights-JS/blob/master/API-reference.md).

## Installation

With npm:
```bash
npm install appinsights-usage -save
```

## Usage

Include following lines to index.js:

```javascript
  var AppInsightsUsage = require('appinsights-usage');
  AppInsightsUsage.init({instrumentationKey:'xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxxx'});
```

To see this metric in Azure portal you need to navigate to Application Insights resource, select Metrics Explorer from the top menu and configure one of the empty charts to display Custom metrics "Session Duration (seconds)" . It can take up to 10 minutes for new custom metric to appear in Azure Portal.

