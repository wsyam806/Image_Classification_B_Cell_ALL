**Background Problem**

**B-Cell Acute Lymphoblastic Leukemia**

Acute lymphocytic leukemia (ALL) is a type of cancer that affects your
blood and bone marrow.

According to the National Cancer InstituteTrusted Source, B-cell acute
lymphoblastic leukemia is the most common type of ALL in both children
and adults.

When you're diagnosed with ALL, you'll also be diagnosed with a subtype,
B-cell or T-cell. Your subtype will affect your treatment.

You'll likely receive chemotherapy and medication as the first round of
treatment. Other treatments will depend on how your body responds to the
chemotherapy.

B-cell acute lymphoblastic leukemia is a serious condition, but with
treatment, remission is possible.

## **What is B-cell acute lymphoblastic leukemia?**

B-cell acute lymphoblastic leukemia is a type of acute lymphoblastic
leukemia (ALL) that causes you to have many immature white blood cells,
known as B-cell lymphoblasts, in your bloodstream and bone marrow.

B-cell acute lymphoblastic leukemia is the most common subtype of ALL,
and causes 75 percent of ALL cases in adults, according to the Leukemia
and Lymphoma Society. It usually progresses quickly.

When you have B-cell acute lymphoblastic leukemia, your system makes the
immature white blood cells instead of the mature white blood cells your
body needs.

The immature cells do not perform necessary tasks such as fighting
infections. As the immature cells build up in your body, there isn't
room for healthy, mature cells.

## **Can you prevent B-cell acute lymphoblastic leukemia?**

Since there is no known cause of B-cell acute lymphoblastic leukemia,
there is no way to prevent it.

You can try to avoid any harmful risk factors you can control, such as
smoking. However, there is no guarantee that this will prevent you from
developing B-cell acute lymphoblastic leukemia.

## **How is B-cell acute lymphoblastic leukemia treated?**

There are many types of treatment for B-cell acute lymphoblastic
leukemia.

The first phase of treatment, known as induction therapy, aims to
destroy the lymphoblasts and get your blood cell production stabilized.
You'll be in remission once this occurs, but you'll still need
treatment.

You'll then have additional treatment, known as post-remission therapy,
to destroy any remaining cancer cells in your body.

You'll typically follow up a few years of what's called maintenance
therapy. Maintenance therapy prevents the cancer cells from regrowing.

Treatments you might receive throughout these phases include:

-   **Chemotherapy**. You'll receive chemotherapy during the first phase
    of your treatment to destroy the cancer cells. You might also
    receive chemotherapy in the post-remission and maintenance therapy
    phases.
-   **Radiation**. Radiation therapy destroys cancer cells using beams
    similar to X-rays. You might need radiation if your cancer has
    spread.
-   **Targeted therapy**. You'll be prescribed medication to target the
    "errors" in the cancer cells. This can cause them to die off.
    Targeted therapy is generally used in the first phase of treatment
    along with chemotherapy.
-   **Stem cell transplants**. Stem cell transplants replace the bone
    marrow affected by cancer cells with new, healthy bone marrow. It's
    generally used for relapses.
-   **Immunotherapy**. Immunotherapy boosts your body's natural immune
    system to help fight cancer. You might receive this treatment if you
    have a relapse.
-   **Chimeric antigen receptor (CAR)-T cell therapy**. CAR-T cell
    therapy is a treatment that works with your body's T-cells to get
    them to fight the cancer cells. This treatment is generally used in
    children and young adults.

Source :
<https://www.healthline.com/health/leukemia/b-cell-acute-lymphoblastic-leukemia#bottom-line>

**About Dataset**

> The images of this dataset were prepared in the bone marrow laboratory
> of Taleqani Hospital (Tehran, Iran). This dataset consisted of 3242
> PBS images from 89 patients suspected of ALL, whose blood samples were
> prepared and stained by skilled laboratory staff. This dataset is
> divided into two classes benign and malignant. The former comprises
> hematogenous, and the latter is the ALL group with three subtypes of
> malignant lymphoblasts: Early Pre-B, Pre-B, and Pro-B ALL. All the
> images were taken by using a Zeiss camera in a microscope with a 100x
> magnification and saved as JPG files. A specialist using the flow
> cytometry tool made the definitive determination of the types and
> subtypes of these cells.
>
**XI. CONCLUSION** 

Four different models were evaluated in this study: Sequential (Sq),
Functional (Fnc), Improved Sequential (Sq Improve), and Improved
Functional (Fnc Improve).

The evaluation was performed on a test dataset to assess each model\'s
performance. The metrics used for evaluation were Test Loss and Test
Accuracy.

Based on the evaluation results, the best-performing model is \"Improved
Functional\" (Fnc Improve) with a Test Loss of 0.128467 and Test
Accuracy of 0.958834. It outperforms all other models in both metrics.

The second-best model is \"Improved Sequential\" (Sq Improve) with a
Test Loss of 0.170985 and Test Accuracy of 0.948542. While it didn\'t
achieve the same level of accuracy as the \"Improved Functional\" model,
it still performed better than the original \"Sequential\" and
\"Functional\" models.

## Model Inference

Both the Functional API Improved CNN model and the Sequential API
Improved CNN model have exhibited impressive performance in accurately
classifying data on the test dataset. The Functional API model slightly
outperformed the Sequential API model, achieving an accuracy of 95.47%
compared to 94.65%.
