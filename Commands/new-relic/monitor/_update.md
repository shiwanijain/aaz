# [Command] _new-relic monitor update_

Update an existing New Relic monitor resource from your Azure subscription

## Versions

### [2022-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL25ld3JlbGljLm9ic2VydmFiaWxpdHkvbW9uaXRvcnMve30=/2022-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/newrelic.observability/monitors/{} 2022-07-01 -->

### [2024-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL25ld3JlbGljLm9ic2VydmFiaWxpdHkvbW9uaXRvcnMve30=/2024-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/newrelic.observability/monitors/{} 2024-01-01 -->

#### examples

- Update a NewRelicMonitorResource
    ```bash
        new-relic monitor update --resource-group MyResourceGroup --name MyNewRelicMonitor --user-info first-name="vdftzcggiref" last-name="bcsztgqovdlmzf" email-address="UserEmail@123.com" phone-number="123456" --plan-data billing-cycle="MONTHLY" effective-date='2022-10-25T15:14:33+02:00' plan-details="newrelic-pay-as-you-go-free-live@TIDgmz7xq9ge3py@PUBIDnewrelicinc1635200720692.newrelic_liftr_payg" usage-type="PAYG" --account-creation-source "LIFTR" --org-creation-source "LIFTR" --tags key6976=oaxfhf
    ```

### [2026-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL25ld3JlbGljLm9ic2VydmFiaWxpdHkvbW9uaXRvcnMve30=/2026-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/newrelic.observability/monitors/{} 2026-06-01 -->

#### examples

- Update a New Relic monitor
    ```bash
        new-relic monitor update --resource-group myResourceGroup --monitor-name myNewRelicMonitor --user-info first-name=Example last-name=Customer email-address=customer@contoso.com phone-number="" --plan-data billing-cycle=MONTHLY effective-date=2026-08-27T00:00:00Z plan-details="newrelic-pay-as-you-go-free-live@TIDn7ja87drquhy@PUBIDnewrelicinc1635200720692.newrelic_liftr_payg_2025" usage-type=PAYG --saas-data saas-resource-id="/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/mySaaSResourceGroup/providers/Microsoft.SaaS/resources/myNewRelicSaaS" --tags environment=production
    ```
